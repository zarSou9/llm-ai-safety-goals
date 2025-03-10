### Paper

```json
{
	"id": "https://arxiv.org/pdf/2211.14946.pdf",
	"arxiv_id": "2211.14946",
	"url": "https://arxiv.org/pdf/2211.14946.pdf",
	"title": "Self-Destructing Models: Increasing the Costs of Harmful Dual Uses of Foundation Models",
	"published_date": "2023-11-16T00:00:00.000Z",
	"abstract": "A growing ecosystem of large, open-source foundation models has reduced the labeled data and technical expertise necessary to apply machine learning to many new problems. Yet foundation models pose a clear dual-use risk, indiscriminately reducing the costs of building both harmful and beneficial machine learning systems. Policy tools such as restricted model access and export controls are the primary methods currently used to mitigate such dual-use risks. In this work, we review potential safe-release strategies and argue that both policymakers and AI researchers would benefit from fundamentally new technologies enabling more precise control over the downstream usage of open-source foundation models. We propose one such approach: the task blocking paradigm, in which foundation models are trained with an additional mechanism to impede adaptation to harmful tasks without sacrificing performance on desirable tasks. We call the resulting models self-destructing models, inspired by mechanisms that prevent adversaries from using tools for harmful purposes. We present an algorithm for training self-destructing models leveraging techniques from meta-learning and adversarial learning, which we call meta-learned adversarial censoring (MLAC). In a small-scale experiment, we show MLAC can largely prevent a BERT-style model from being re-purposed to perform gender identification without harming the model's ability to perform profession classification.",
	"citation_count": 42,
	"influential_citation_count": 2,
	"ref": "21387"
}
```

### Explanation

This paper proposes a technical approach called "self-destructing models" that aims to prevent foundation models from being misused for harmful purposes while preserving their beneficial uses, specifically by incorporating mechanisms during training that make it difficult to adapt the models for undesirable tasks. This is relevant to AI safety as it explores ways to maintain control over AI systems' capabilities and prevent their misuse, though it focuses more on near-term applications rather than existential risks from agentic AI systems.
