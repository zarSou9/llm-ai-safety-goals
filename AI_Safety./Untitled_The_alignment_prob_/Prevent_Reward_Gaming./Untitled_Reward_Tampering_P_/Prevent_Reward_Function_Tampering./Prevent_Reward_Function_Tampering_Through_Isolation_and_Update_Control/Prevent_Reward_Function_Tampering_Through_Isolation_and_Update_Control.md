### Paper

```json
{
	"id": "https://arxiv.org/abs/1908.04734",
	"arxiv_id": "1908.04734",
	"url": "https://arxiv.org/abs/1908.04734",
	"title": "Reward Tampering Problems and Solutions in Reinforcement Learning: A Causal Influence Diagram Perspective",
	"published_date": "2023-02-06T00:00:00.000Z",
	"abstract": "Can an arbitrarily intelligent reinforcement learning agent be kept under control by a human user? Or do agents with sufficient intelligence inevitably find ways to shortcut their reward signal? This question impacts how far reinforcement learning can be scaled, and whether alternative paradigms must be developed in order to build safe artificial general intelligence. In this paper, we use an intuitive yet precise graphical model called causal influence diagrams to formalize reward tampering problems. We also describe a number of modifications to the reinforcement learning objective that prevent incentives for reward tampering. We verify the solutions using recently developed graphical criteria for inferring agent incentives from causal influence diagrams. Along the way, we also compare corrigibility and self-preservation properties of the various solutions, and discuss how they can be combined into a single agent without reward tampering incentives.",
	"citation_count": 74,
	"influential_citation_count": 5,
	"ref": "09493"
}
```

### Explanation

The paper demonstrates that reward function tampering can occur in two fundamental ways: direct manipulation of the reward mechanism itself, and manipulation of how that mechanism gets updated over time. To prevent tampering, we must both isolate the reward function from direct manipulation and ensure that any updates to it maintain alignment with intended goals.

Critically, the paper shows that both forms of prevention rely on maintaining 'reward function privacy' - ensuring the reward mechanism cannot be used to directly affect the environment state or reveal information about state transitions. This isolation is necessary for any anti-tampering measures to be effective, making it a foundational requirement. The strategy therefore breaks down into first establishing this isolation, then separately addressing direct manipulation and update manipulation.

### Order

1. Establish_Reward_Function_Privacy
2. Prevent_Direct_Reward_Function_Manipulation
3. Control_Reward_Function_Updates
