### Paper

```json
{
	"id": "https://arxiv.org/abs/2405.17653",
	"arxiv_id": "2405.17653",
	"url": "https://arxiv.org/abs/2405.17653",
	"title": "InversionView: A General-Purpose Method for Reading Information from Neural Activations",
	"published_date": "2024-05-27T00:00:00.000Z",
	"abstract": "The inner workings of neural networks can be better understood if we can fully decipher the information encoded in neural activations. In this paper, we argue that this information is embodied by the subset of inputs that give rise to similar activations. We propose InversionView, which allows us to practically inspect this subset by sampling from a trained decoder model conditioned on activations. This helps uncover the information content of activation vectors, and facilitates understanding of the algorithms implemented by transformer models. We present four case studies where we investigate models ranging from small transformers to GPT-2. In these studies, we show that InversionView can reveal clear information contained in activations, including basic information about tokens appearing in the context, as well as more complex information, such as the count of certain tokens, their relative positions, and abstract knowledge about the subject. We also provide causally verified circuits to confirm the decoded information.",
	"citation_count": 2,
	"influential_citation_count": 0,
	"ref": "38611"
}
```

### Explanation

This paper presents InversionView, a method for understanding what information is encoded in neural networks' internal activations by reconstructing inputs that would produce similar activation patterns, which is relevant to algorithm extraction by helping reveal how neural networks process and represent information internally. The approach demonstrates the ability to decode both simple and complex information from model activations, which could aid in translating neural network behaviors into more transparent, verifiable implementations.
