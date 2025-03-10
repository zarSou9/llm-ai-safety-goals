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

The paper's analysis reveals that reward process privacy requires both causal and informational isolation between the reward process and the environment. The causal isolation prevents direct effects in either direction, while informational isolation must address both outward leakage of information from the reward process and inward corruption of information coming into the reward process. This bidirectional approach ensures complete isolation while maintaining the reward process's ability to properly evaluate states.

The paper's three key assumptions about reward process privacy (Assumptions 1-3) map onto these aspects - Assumption 1 addresses causal isolation, while Assumptions 2 and 3 address different aspects of information flow. The paper's extensive discussion of belief states and RF-input tampering further highlights the importance of protecting information integrity in both directions.

### Order

1. Ensure_Causal_Isolation
2. Prevent_Information_Leakage
3. Maintain_Information_Integrity
