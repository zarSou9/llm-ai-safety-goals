### Paper

```json
{
	"id": "https://arxiv.org/abs/2112.00826",
	"arxiv_id": "2112.00826",
	"url": "https://arxiv.org/abs/2112.00826",
	"title": "Inducing Causal Structure for Interpretable Neural Networks",
	"published_date": "2021-12-01T00:00:00.000Z",
	"abstract": "In many areas, we have well-founded insights about causal structure that would be useful to bring into our trained models while still allowing them to learn in a data-driven fashion. To achieve this, we present the new method of interchange intervention training (IIT). In IIT, we (1) align variables in a causal model (e.g., a deterministic program or Bayesian network) with representations in a neural model and (2) train the neural model to match the counterfactual behavior of the causal model on a base input when aligned representations in both models are set to be the value they would be for a source input. IIT is fully differentiable, flexibly combines with other objectives, and guarantees that the target causal model is a causal abstraction of the neural model when its loss is zero. We evaluate IIT on a structural vision task (MNIST-PVR), a navigational language task (ReaSCAN), and a natural language inference task (MQNLI). We compare IIT against multi-task training objectives and data augmentation. In all our experiments, IIT achieves the best results and produces neural models that are more interpretable in the sense that they more successfully realize the target causal model.",
	"citation_count": 65,
	"influential_citation_count": 5,
	"ref": "45929"
}
```

### Explanation

This paper presents a method called interchange intervention training (IIT) that allows neural networks to learn causal structures aligned with known causal models, making the networks more interpretable while preserving their performance. This is relevant to algorithm extraction as it provides a way to make neural networks more transparent and verifiable by incorporating known causal relationships into their structure, though it requires having a causal model to align with rather than extracting one from a black box.
