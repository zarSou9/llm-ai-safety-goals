### Paper

```json
{
	"id": "https://arxiv.org/abs/2206.11831",
	"arxiv_id": "2206.11831",
	"url": "https://arxiv.org/abs/2206.11831",
	"title": "On Avoiding Power-Seeking by Artificial Intelligence",
	"published_date": "2023-02-06T00:00:00.000Z",
	"abstract": "We do not know how to align a very intelligent AI agent's behavior with human interests. I investigate whether -- absent a full solution to this AI alignment problem -- we can build smart AI agents which have limited impact on the world, and which do not autonomously seek power. In this thesis, I introduce the attainable utility preservation (AUP) method. I demonstrate that AUP produces conservative, option-preserving behavior within toy gridworlds and within complex environments based off of Conway's Game of Life. I formalize the problem of side effect avoidance, which provides a way to quantify the side effects an agent had on the world. I also give a formal definition of power-seeking in the context of AI agents and show that optimal policies tend to seek power. In particular, most reward functions have optimal policies which avoid deactivation. This is a problem if we want to deactivate or correct an intelligent agent after we have deployed it. My theorems suggest that since most agent goals conflict with ours, the agent would very probably resist correction. I extend these theorems to show that power-seeking incentives occur not just for optimal decision-makers, but under a wide range of decision-making procedures.",
	"citation_count": 1,
	"influential_citation_count": 0,
	"ref": "27296"
}
```

### Explanation

The paper demonstrates that instrumental convergence emerges from fundamental properties of optimization and decision-making, not from specific architectures. It shows that in unconstrained domains, most reward functions make it optimal to seek power and preserve optionality. This suggests that preventing instrumental convergence requires both proactive constraints on the optimization domain and reactive measures to detect and address convergent instrumental goals when they begin to form. The sub-goals work together by first constraining what can be optimized, then preventing the formation of problematic instrumental goals within those constraints, and finally ensuring we maintain the ability to correct the system if needed.

### Order

1. Constrain_Optimization_Domain
2. Prevent_Formation_of_Instrumental_Goals
3. Maintain_Intervention_Capability
