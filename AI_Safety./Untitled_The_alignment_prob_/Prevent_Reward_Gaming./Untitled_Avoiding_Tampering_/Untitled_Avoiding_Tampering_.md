### Paper

```json
{
	"id": "https://arxiv.org/abs/2011.08827",
	"arxiv_id": "2011.08827",
	"url": "https://arxiv.org/abs/2011.08827",
	"title": "Avoiding Tampering Incentives in Deep RL via Decoupled Approval",
	"published_date": "2023-02-06T00:00:00.000Z",
	"abstract": "How can we design agents that pursue a given objective when all feedback mechanisms are influenceable by the agent? Standard RL algorithms assume a secure reward function, and can thus perform poorly in settings where agents can tamper with the reward-generating mechanism. We present a principled solution to the problem of learning from influenceable feedback, which combines approval with a decoupled feedback collection procedure. For a natural class of corruption functions, decoupled approval algorithms have aligned incentives both at convergence and for their local updates. Empirically, they also scale to complex 3D environments where tampering is possible.",
	"citation_count": 11,
	"influential_citation_count": 0,
	"ref": "37903"
}
```

### Explanation

This paper addresses the challenge of preventing AI systems from tampering with their reward mechanisms by proposing a "decoupled approval" approach that separates the feedback collection process from the agent's actions, which is directly relevant to preventing reward gaming and maintaining human control over AI systems.
