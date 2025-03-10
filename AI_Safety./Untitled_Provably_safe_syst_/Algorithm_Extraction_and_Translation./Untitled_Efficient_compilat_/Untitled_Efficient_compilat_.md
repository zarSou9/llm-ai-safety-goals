### Paper

```json
{
	"id": "https://arxiv.org/abs/2402.01353",
	"arxiv_id": "2402.01353",
	"url": "https://arxiv.org/abs/2402.01353",
	"title": "Efficient compilation of expressive problem space specifications to neural network solvers",
	"published_date": "2024-01-24T00:00:00.000Z",
	"abstract": "Recent work has described the presence of the embedding gap in neural network verification. On one side of the gap is a high-level specification about the network's behaviour, written by a domain expert in terms of the interpretable problem space. On the other side are a logically-equivalent set of satisfiability queries, expressed in the uninterpretable embedding space in a form suitable for neural network solvers. In this paper we describe an algorithm for compiling the former to the latter. We explore and overcome complications that arise from targeting neural network solvers as opposed to standard SMT solvers.",
	"citation_count": 0,
	"influential_citation_count": 0,
	"ref": "16789"
}
```

### Explanation

This paper focuses on developing methods to translate high-level behavioral specifications into formal verification queries that can be used with neural network solvers, which is relevant to algorithm extraction by helping bridge the gap between human-interpretable specifications and the internal representations of neural networks. While this work approaches the translation direction opposite to the sub-goal (going from specifications to neural networks rather than neural networks to verifiable code), the techniques developed could inform bidirectional translation methods.
