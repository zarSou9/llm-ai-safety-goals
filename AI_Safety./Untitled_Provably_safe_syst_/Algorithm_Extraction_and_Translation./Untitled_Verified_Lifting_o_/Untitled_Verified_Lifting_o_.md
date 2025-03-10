### Paper

```json
{
	"id": "https://arxiv.org/abs/2412.20992",
	"arxiv_id": "2412.20992",
	"url": "https://arxiv.org/abs/2412.20992",
	"title": "Verified Lifting of Deep learning Operators",
	"published_date": "2024-12-30T00:00:00.000Z",
	"abstract": "Deep learning operators are fundamental components of modern deep learning frameworks. With the growing demand for customized operators, it has become increasingly common for developers to create their own. However, designing and implementing operators is complex and error-prone, due to hardware-specific optimizations and the need for numerical stability. There is a pressing need for tools that can summarize the functionality of both existing and user-defined operators. To address this gap, this work introduces a novel framework for the verified lifting of deep learning operators, which synthesizes high-level mathematical formulas from low-level implementations. Our approach combines symbolic execution, syntax-guided synthesis, and SMT-based verification to produce readable and formally verified mathematical formulas. In synthesis, we employ a combination of top-down and bottom-up strategies to explore the vast search space efficiently; In verification, we design invariant synthesis patterns and leverage SMT solvers to validate the correctness of the derived summaries; In simplification, we use egraph-based techniques with custom rules to restore complex formulas to their natural, intuitive forms. Evaluated on a dataset of deep learning operators implemented in Triton from the real world, our method demonstrates the effectiveness of synthesis and verification compared to existing techniques. This framework bridges the gap between low-level implementations and high-level abstractions, improving understanding and reliability in deep learning operator development.",
	"citation_count": 0,
	"influential_citation_count": 0,
	"ref": "21101"
}
```

### Explanation

This paper presents a framework for automatically extracting and verifying high-level mathematical formulas from low-level implementations of deep learning operators, which directly supports the sub-goal by providing a method to make black-box neural network components more transparent and verifiable while preserving their functionality. The approach combines multiple formal methods techniques to synthesize readable and provably correct mathematical descriptions of neural network operations.
