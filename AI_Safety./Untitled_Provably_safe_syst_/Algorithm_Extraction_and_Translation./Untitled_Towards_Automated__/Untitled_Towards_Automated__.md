### Paper

```json
{
	"id": "https://arxiv.org/abs/2304.14997",
	"arxiv_id": "2304.14997",
	"url": "https://arxiv.org/abs/2304.14997",
	"title": "Towards Automated Circuit Discovery for Mechanistic Interpretability",
	"published_date": "2023-04-28T00:00:00.000Z",
	"abstract": "Through considerable effort and intuition, several recent works have reverse-engineered nontrivial behaviors of transformer models. This paper systematizes the mechanistic interpretability process they followed. First, researchers choose a metric and dataset that elicit the desired model behavior. Then, they apply activation patching to find which abstract neural network units are involved in the behavior. By varying the dataset, metric, and units under investigation, researchers can understand the functionality of each component. We automate one of the process' steps: to identify the circuit that implements the specified behavior in the model's computational graph. We propose several algorithms and reproduce previous interpretability results to validate them. For example, the ACDC algorithm rediscovered 5/5 of the component types in a circuit in GPT-2 Small that computes the Greater-Than operation. ACDC selected 68 of the 32,000 edges in GPT-2 Small, all of which were manually found by previous work. Our code is available at https://github.com/ArthurConmy/Automatic-Circuit-Discovery.",
	"citation_count": 200,
	"influential_citation_count": 25,
	"ref": "76843"
}
```

### Explanation

This paper develops automated methods for identifying the specific neural circuits responsible for particular behaviors in transformer models, which is relevant to algorithm extraction by helping systematically reverse-engineer how neural networks implement specific computational functions rather than treating them as black boxes.
