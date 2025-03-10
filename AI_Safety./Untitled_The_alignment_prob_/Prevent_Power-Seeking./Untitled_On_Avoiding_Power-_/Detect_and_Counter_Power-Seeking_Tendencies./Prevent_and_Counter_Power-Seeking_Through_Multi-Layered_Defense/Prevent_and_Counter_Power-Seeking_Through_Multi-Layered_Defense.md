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

The paper demonstrates that power-seeking tendencies arise not from specific architectures, but from fundamental properties of optimization and decision-making. This insight suggests we need a multi-layered approach that addresses both the root causes and manifestations of power-seeking behavior. The strategy focuses first on preventing the conditions that give rise to power-seeking tendencies - unbounded optimization and instrumental convergence. Then it ensures systems remain amenable to human oversight and correction. Finally, it provides methods to detect and address any power-seeking behaviors that emerge despite the other protections.

### Order

1. Constrain_Optimization_Scope
2. Prevent_Instrumental_Convergence
3. Maintain_Option-Preserving_Behavior
4. Detect_and_Counter_Power-Seeking_Tendencies
