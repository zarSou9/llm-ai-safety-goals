### Paper

```json
{
	"id": "https://arxiv.org/abs/2310.12773",
	"arxiv_id": "2310.12773",
	"url": "https://arxiv.org/abs/2310.12773",
	"title": "Safe RLHF: Safe Reinforcement Learning from Human Feedback",
	"published_date": "2023-10-19T00:00:00.000Z",
	"abstract": "With the development of large language models (LLMs), striking a balance between the performance and safety of AI systems has never been more critical. However, the inherent tension between the objectives of helpfulness and harmlessness presents a significant challenge during LLM training. To address this issue, we propose Safe Reinforcement Learning from Human Feedback (Safe RLHF), a novel algorithm for human value alignment. Safe RLHF explicitly decouples human preferences regarding helpfulness and harmlessness, effectively avoiding the crowdworkers' confusion about the tension and allowing us to train separate reward and cost models. We formalize the safety concern of LLMs as an optimization task of maximizing the reward function while satisfying specified cost constraints. Leveraging the Lagrangian method to solve this constrained problem, Safe RLHF dynamically adjusts the balance between the two objectives during fine-tuning. Through a three-round fine-tuning using Safe RLHF, we demonstrate a superior ability to mitigate harmful responses while enhancing model performance compared to existing value-aligned algorithms. Experimentally, we fine-tuned the Alpaca-7B using Safe RLHF and aligned it with collected human preferences, significantly improving its helpfulness and harmlessness according to human evaluations.",
	"citation_count": 205,
	"influential_citation_count": 43,
	"ref": "88813"
}
```

### Explanation

This paper introduces Safe RLHF, an algorithm that separately optimizes for helpfulness and harmlessness in language models during training, using distinct reward and cost models to better align AI systems with human values while preventing harmful outputs. This directly addresses AI safety by providing a concrete mechanism to maintain control over AI behavior and reduce risks of misalignment during the training process.
