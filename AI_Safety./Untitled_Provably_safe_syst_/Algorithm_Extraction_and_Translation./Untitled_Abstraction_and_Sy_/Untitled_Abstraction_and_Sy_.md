### Paper

```json
{
	"id": "https://arxiv.org/abs/2103.03704",
	"arxiv_id": "2103.03704",
	"url": "https://arxiv.org/abs/2103.03704",
	"title": "Abstraction and Symbolic Execution of Deep Neural Networks with Bayesian Approximation of Hidden Features",
	"published_date": "2021-03-05T00:00:00.000Z",
	"abstract": "Intensive research has been conducted on the verification and validation of deep neural networks (DNNs), aiming to understand if, and how, DNNs can be applied to safety critical applications. However, existing verification and validation techniques are limited by their scalability, over both the size of the DNN and the size of the dataset. In this paper, we propose a novel abstraction method which abstracts a DNN and a dataset into a Bayesian network (BN). We make use of dimensionality reduction techniques to identify hidden features that have been learned by hidden layers of the DNN, and associate each hidden feature with a node of the BN. On this BN, we can conduct probabilistic inference to understand the behaviours of the DNN processing data. More importantly, we can derive a runtime monitoring approach to detect in operational time rare inputs and covariate shift of the input data. We can also adapt existing structural coverage-guided testing techniques (i.e., based on low-level elements of the DNN such as neurons), in order to generate test cases that better exercise hidden features. We implement and evaluate the BN abstraction technique using our DeepConcolic tool available at https://github.com/TrustAI/DeepConcolic.",
	"citation_count": 10,
	"influential_citation_count": 0,
	"ref": "24733"
}
```

### Explanation

This paper proposes a method to abstract deep neural networks into more interpretable Bayesian networks by identifying and mapping learned hidden features, which is relevant to algorithm extraction as it provides a way to make black-box neural networks more transparent and analyzable, though it falls short of full capability-preserving code translation.
