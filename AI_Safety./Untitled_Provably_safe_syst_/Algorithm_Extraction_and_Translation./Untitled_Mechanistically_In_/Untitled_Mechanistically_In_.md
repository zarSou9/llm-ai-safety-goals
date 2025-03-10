### Paper

```json
{
	"id": "https://arxiv.org/abs/2407.13594",
	"arxiv_id": "2407.13594",
	"url": "https://arxiv.org/abs/2407.13594",
	"title": "Mechanistically Interpreting a Transformer-based 2-SAT Solver: An Axiomatic Approach",
	"published_date": "2024-07-18T00:00:00.000Z",
	"abstract": "Mechanistic interpretability aims to reverse engineer the computation performed by a neural network in terms of its internal components. Although there is a growing body of research on mechanistic interpretation of neural networks, the notion of a mechanistic interpretation itself is often ad-hoc. Inspired by the notion of abstract interpretation from the program analysis literature that aims to develop approximate semantics for programs, we give a set of axioms that formally characterize a mechanistic interpretation as a description that approximately captures the semantics of the neural network under analysis in a compositional manner. We use these axioms to guide the mechanistic interpretability analysis of a Transformer-based model trained to solve the well-known 2-SAT problem. We are able to reverse engineer the algorithm learned by the model -- the model first parses the input formulas and then evaluates their satisfiability via enumeration of different possible valuations of the Boolean input variables. We also present evidence to support that the mechanistic interpretation of the analyzed model indeed satisfies the stated axioms.",
	"citation_count": 0,
	"influential_citation_count": 0,
	"ref": "38234"
}
```

### Explanation

This paper develops a formal framework for understanding how transformer neural networks process information internally and applies it to reverse engineer the specific algorithm learned by a transformer solving 2-SAT problems, demonstrating progress toward extracting interpretable algorithms from neural networks. This directly relates to the algorithm extraction sub-goal by showing how we can convert a black-box neural network's learned behavior into an understandable, verifiable algorithm while preserving its capabilities.
