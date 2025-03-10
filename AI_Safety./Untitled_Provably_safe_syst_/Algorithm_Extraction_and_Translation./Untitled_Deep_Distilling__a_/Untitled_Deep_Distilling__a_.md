### Paper

```json
{
	"id": "https://arxiv.org/abs/2111.08275",
	"arxiv_id": "2111.08275",
	"url": "https://arxiv.org/abs/2111.08275",
	"title": "Deep Distilling: automated code generation using explainable deep learning",
	"published_date": "2021-11-16T00:00:00.000Z",
	"abstract": "Human reasoning can distill principles from observed patterns and generalize them to explain and solve novel problems. The most powerful artificial intelligence systems lack explainability and symbolic reasoning ability, and have therefore not achieved supremacy in domains requiring human understanding, such as science or common sense reasoning. Here we introduce deep distilling, a machine learning method that learns patterns from data using explainable deep learning and then condenses it into concise, executable computer code. The code, which can contain loops, nested logical statements, and useful intermediate variables, is equivalent to the neural network but is generally orders of magnitude more compact and human-comprehensible. On a diverse set of problems involving arithmetic, computer vision, and optimization, we show that deep distilling generates concise code that generalizes out-of-distribution to solve problems orders-of-magnitude larger and more complex than the training data. For problems with a known ground-truth rule set, deep distilling discovers the rule set exactly with scalable guarantees. For problems that are ambiguous or computationally intractable, the distilled rules are similar to existing human-derived algorithms and perform at par or better. Our approach demonstrates that unassisted machine intelligence can build generalizable and intuitive rules explaining patterns in large datasets that would otherwise overwhelm human reasoning.",
	"citation_count": 2,
	"influential_citation_count": 0,
	"ref": "04892"
}
```

### Explanation

This paper presents "deep distilling," a method that can automatically convert neural networks into human-readable and verifiable computer code while preserving their functionality, directly addressing the sub-goal of extracting algorithms from black-box AI systems into transparent implementations. The approach shows promise in generating concise code that can generalize beyond training data and, in some cases, exactly recover known underlying rules.
