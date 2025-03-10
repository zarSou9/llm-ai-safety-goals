### Paper

```json
{
	"id": "https://arxiv.org/abs/2306.01128",
	"arxiv_id": "2306.01128",
	"url": "https://arxiv.org/abs/2306.01128",
	"title": "Learning Transformer Programs",
	"published_date": "2023-06-01T00:00:00.000Z",
	"abstract": "Recent research in mechanistic interpretability has attempted to reverse-engineer Transformer models by carefully inspecting network weights and activations. However, these approaches require considerable manual effort and still fall short of providing complete, faithful descriptions of the underlying algorithms. In this work, we introduce a procedure for training Transformers that are mechanistically interpretable by design. We build on RASP [Weiss et al., 2021], a programming language that can be compiled into Transformer weights. Instead of compiling human-written programs into Transformers, we design a modified Transformer that can be trained using gradient-based optimization and then automatically converted into a discrete, human-readable program. We refer to these models as Transformer Programs. To validate our approach, we learn Transformer Programs for a variety of problems, including an in-context learning task, a suite of algorithmic problems (e.g. sorting, recognizing Dyck languages), and NLP tasks including named entity recognition and text classification. The Transformer Programs can automatically find reasonable solutions, performing on par with standard Transformers of comparable size; and, more importantly, they are easy to interpret. To demonstrate these advantages, we convert Transformers into Python programs and use off-the-shelf code analysis tools to debug model errors and identify the\"circuits\"used to solve different sub-problems. We hope that Transformer Programs open a new path toward the goal of intrinsically interpretable machine learning.",
	"citation_count": 30,
	"influential_citation_count": 2,
	"ref": "31130"
}
```

### Explanation

This paper presents a method for training Transformer models that can be automatically converted into human-readable programs, making their internal algorithms transparent and analyzable - directly addressing the sub-goal of extracting interpretable algorithms from neural networks. The approach demonstrates success on various tasks while maintaining performance comparable to standard Transformers.
