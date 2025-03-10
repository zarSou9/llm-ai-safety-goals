### Paper

```json
{
	"id": "https://arxiv.org/abs/2304.00989",
	"arxiv_id": "2304.00989",
	"url": "https://arxiv.org/abs/2304.00989",
	"title": "Neuro-Symbolic Execution of Generic Source Code",
	"published_date": "2023-03-23T00:00:00.000Z",
	"abstract": "Can a Python program be executed statement-by-statement by neural networks composed according to the source code? We formulate the Neuro-Symbolic Execution Problem and introduce Neural Interpretation (NI), the first neural model for the execution of generic source code that allows missing definitions. NI preserves source code structure, where every variable has a vector encoding, and every function executes a neural network. NI is a novel neural model of computers with a compiler architecture that can assemble neural layers\"programmed\"by source code. NI is the first neural model capable of executing Py150 dataset programs, including library functions without concrete inputs, and it can be trained with flexible code understanding objectives. We demonstrate white-box execution without concrete inputs for variable misuse localization and repair.",
	"citation_count": 0,
	"influential_citation_count": 0,
	"ref": "42473"
}
```

### Explanation

This paper introduces Neural Interpretation, a system that can execute Python code using neural networks while maintaining interpretability of the code's structure, which is relevant to algorithm extraction by demonstrating a potential bridge between neural and symbolic representations of programs. The approach allows for white-box analysis of program execution, which could contribute to making AI systems more transparent and verifiable.
