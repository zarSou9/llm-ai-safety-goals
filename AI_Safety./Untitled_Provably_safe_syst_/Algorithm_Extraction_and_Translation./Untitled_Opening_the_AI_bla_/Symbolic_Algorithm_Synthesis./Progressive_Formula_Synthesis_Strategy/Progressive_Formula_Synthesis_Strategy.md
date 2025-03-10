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

The core strategy is to break down symbolic formula synthesis into three progressive phases that build upon each other. First, we analyze the computational patterns to determine what types of symbolic representations and operations would be appropriate for capturing the behavior. This creates a well-defined search space for the second phase, which focuses on discovering any valid symbolic formulas that reproduce the observed behavior. Finally, we optimize these initial formulas to find the minimal equivalent expressions.

This approach is informed by the paper's successful MIPS implementation, which demonstrated that effective symbolic synthesis requires first understanding the representation type (Boolean vs Integer) before applying appropriate discovery techniques. However, we abstract this to be more general than the paper's specific implementation choices. The three phases are designed to be sequential and minimally overlapping, while collectively ensuring we discover the simplest possible formulas that exactly capture the computational behavior.
