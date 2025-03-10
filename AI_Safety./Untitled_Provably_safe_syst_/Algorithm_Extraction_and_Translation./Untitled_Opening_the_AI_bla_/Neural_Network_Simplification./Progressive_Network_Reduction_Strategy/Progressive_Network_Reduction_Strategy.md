### Paper

```json
{
	"id": "https://arxiv.org/abs/2402.05110",
	"arxiv_id": "2402.05110",
	"url": "https://arxiv.org/abs/2402.05110",
	"title": "Opening the AI black box: program synthesis via mechanistic interpretability",
	"published_date": "2024-02-07T00:00:00.000Z",
	"abstract": "We present MIPS, a novel method for program synthesis based on automated mechanistic interpretability of neural networks trained to perform the desired task, auto-distilling the learned algorithm into Python code. We test MIPS on a benchmark of 62 algorithmic tasks that can be learned by an RNN and find it highly complementary to GPT-4: MIPS solves 32 of them, including 13 that are not solved by GPT-4 (which also solves 30). MIPS uses an integer autoencoder to convert the RNN into a finite state machine, then applies Boolean or integer symbolic regression to capture the learned algorithm. As opposed to large language models, this program synthesis technique makes no use of (and is therefore not limited by) human training data such as algorithms and code from GitHub. We discuss opportunities and challenges for scaling up this approach to make machine-learned models more interpretable and trustworthy.",
	"citation_count": 9,
	"influential_citation_count": 0,
	"ref": "11228"
}
```

### Explanation

The paper demonstrates that neural network simplification can be approached as a sequence of transformations that progressively reduce complexity while preserving functionality. The key insight is to separate this process into three fundamentally distinct types of simplification: architectural, representational, and parametric.

This breakdown follows a natural progression from macro to micro simplification. We first find the minimal architecture capable of performing the task, then simplify how information flows through that architecture by normalizing and canonicalizing internal representations, and finally simplify the individual parameters themselves. Each stage builds on the previous one - for instance, having simpler internal representations makes it easier to identify opportunities for parameter quantization.

### Order

1. Architecture_Minimization
2. Representation_Canonicalization
3. Parameter_Simplification
