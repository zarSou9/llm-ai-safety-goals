### Paper

```json
{
	"id": "https://arxiv.org/abs/2404.14349",
	"arxiv_id": "2404.14349",
	"url": "https://arxiv.org/abs/2404.14349",
	"title": "Automatic Discovery of Visual Circuits",
	"published_date": "2024-04-22T00:00:00.000Z",
	"abstract": "To date, most discoveries of network subcomponents that implement human-interpretable computations in deep vision models have involved close study of single units and large amounts of human labor. We explore scalable methods for extracting the subgraph of a vision model's computational graph that underlies recognition of a specific visual concept. We introduce a new method for identifying these subgraphs: specifying a visual concept using a few examples, and then tracing the interdependence of neuron activations across layers, or their functional connectivity. We find that our approach extracts circuits that causally affect model output, and that editing these circuits can defend large pretrained models from adversarial attacks.",
	"citation_count": 0,
	"influential_citation_count": 0,
	"ref": "50145"
}
```

### Explanation

This paper presents a method for automatically identifying and extracting interpretable neural circuits from vision models that are responsible for specific visual concepts, which is relevant to algorithm extraction by providing a concrete approach for making black-box neural networks more transparent and understandable. The ability to identify and edit these circuits also demonstrates potential for translating neural network components into more verifiable implementations.
