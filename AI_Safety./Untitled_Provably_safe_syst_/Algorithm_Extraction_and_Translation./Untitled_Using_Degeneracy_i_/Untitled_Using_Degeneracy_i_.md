### Paper

```json
{
	"id": "https://arxiv.org/abs/2405.10927",
	"arxiv_id": "2405.10927",
	"url": "https://arxiv.org/abs/2405.10927",
	"title": "Using Degeneracy in the Loss Landscape for Mechanistic Interpretability",
	"published_date": "2024-05-17T00:00:00.000Z",
	"abstract": "Mechanistic Interpretability aims to reverse engineer the algorithms implemented by neural networks by studying their weights and activations. An obstacle to reverse engineering neural networks is that many of the parameters inside a network are not involved in the computation being implemented by the network. These degenerate parameters may obfuscate internal structure. Singular learning theory teaches us that neural network parameterizations are biased towards being more degenerate, and parameterizations with more degeneracy are likely to generalize further. We identify 3 ways that network parameters can be degenerate: linear dependence between activations in a layer; linear dependence between gradients passed back to a layer; ReLUs which fire on the same subset of datapoints. We also present a heuristic argument that modular networks are likely to be more degenerate, and we develop a metric for identifying modules in a network that is based on this argument. We propose that if we can represent a neural network in a way that is invariant to reparameterizations that exploit the degeneracies, then this representation is likely to be more interpretable, and we provide some evidence that such a representation is likely to have sparser interactions. We introduce the Interaction Basis, a tractable technique to obtain a representation that is invariant to degeneracies from linear dependence of activations or Jacobians.",
	"citation_count": 5,
	"influential_citation_count": 0,
	"ref": "29579"
}
```

### Explanation

This paper develops methods to identify and handle redundant or degenerate parameters in neural networks, aiming to create more interpretable representations that could help reverse engineer the underlying algorithms, which directly supports the goal of extracting transparent implementations from black-box AI systems. The authors propose a technique called the "Interaction Basis" that can help reveal the core computational structure of neural networks by removing obfuscating parameters.
