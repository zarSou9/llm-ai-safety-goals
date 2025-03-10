### Paper

```json
{
	"id": "https://arxiv.org/abs/2205.10364",
	"arxiv_id": "2205.10364",
	"url": "https://arxiv.org/abs/2205.10364",
	"title": "Learning to Reverse DNNs from AI Programs Automatically",
	"published_date": "2022-05-20T00:00:00.000Z",
	"abstract": "With the privatization deployment of DNNs on edge devices, the security of on-device DNNs has raised significant concern. To quantify the model leakage risk of on-device DNNs automatically, we propose NNReverse, the first learning-based method which can reverse DNNs from AI programs without domain knowledge. NNReverse trains a representation model to represent the semantics of binary code for DNN layers. By searching the most similar function in our database, NNReverse infers the layer type of a given function's binary code. To represent assembly instructions semantics precisely, NNReverse proposes a more fine-grained embedding model to represent the textual and structural-semantic of assembly functions.",
	"citation_count": 13,
	"influential_citation_count": 1,
	"ref": "23340"
}
```

### Explanation

This paper presents NNReverse, a method for automatically extracting neural network architectures from compiled binary code, which is relevant to algorithm extraction but focuses narrowly on reverse engineering model architectures rather than converting neural networks into verifiable code that preserves their capabilities. The paper's security-focused approach of extracting model details is somewhat tangential to the safety-oriented goals of translating black-box systems into provably safe implementations.
