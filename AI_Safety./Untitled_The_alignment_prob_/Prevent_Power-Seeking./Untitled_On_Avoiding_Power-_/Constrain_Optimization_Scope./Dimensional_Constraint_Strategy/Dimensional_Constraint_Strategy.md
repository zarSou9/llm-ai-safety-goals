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

The paper demonstrates that unconstrained optimization naturally leads to power-seeking behavior through fundamental properties of decision-making and optimization. This suggests that effective constraint requires limiting all key dimensions along which optimization can expand to seek power: the types of objectives that can be specified, the domains over which they can operate, and the temporal horizon over which they can optimize.

By constraining these three fundamental dimensions, we create natural bounds on an AI system's optimization scope while still allowing for effective operation within those bounds. The paper's analysis of retargetability and parameterization shows how carefully restricting these dimensions can prevent the emergence of problematic convergent instrumental goals while preserving desired functionality. This approach ensures that even if a system fully optimizes within its constrained scope, it cannot develop or execute strategies for gaining broader control.

### Order

1. Restrict_Objective_Space
2. Constrain_Operational_Domain
3. Limit_Temporal_Horizon
