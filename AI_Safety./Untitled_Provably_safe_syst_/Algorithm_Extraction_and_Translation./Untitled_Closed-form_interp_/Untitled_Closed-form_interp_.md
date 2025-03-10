### Paper

```json
{
	"id": "http://arxiv.org/abs/2401.04978",
	"arxiv_id": "2401.04978",
	"url": "http://arxiv.org/abs/2401.04978",
	"title": "Closed-form interpretation of neural network classifiers with symbolic gradients",
	"published_date": "2024-01-10T00:00:00.000Z",
	"abstract": "\n I introduce a unified framework for finding a closed-form interpretation of any single neuron in an artificial neural network. Using this framework I demonstrate how to interpret neural network classifiers to reveal closed-form expressions of the concepts encoded in their decision boundaries. In contrast to neural network-based regression, for classification, it is in general impossible to express the neural network in the form of a symbolic equation even if the neural network itself bases its classification on a quantity that can be written as a closed-form equation. The interpretation framework is based on embedding trained neural networks into an equivalence class of functions that encode the same concept. I interpret these neural networks by finding an intersection between the equivalence class and human-readable equations defined by a symbolic search space. The approach is not limited to classifiers or full neural networks and can be applied to arbitrary neurons in hidden layers or latent spaces.",
	"citation_count": 0,
	"influential_citation_count": 0,
	"ref": "74442"
}
```

### Explanation

This paper presents a method for extracting human-readable mathematical equations that represent how individual neurons and neural network classifiers make decisions, which is relevant to algorithm extraction by providing a technique to convert neural network components into transparent, interpretable mathematical expressions. However, the approach is limited to interpreting individual neurons and classification boundaries rather than extracting complete algorithmic behavior.
