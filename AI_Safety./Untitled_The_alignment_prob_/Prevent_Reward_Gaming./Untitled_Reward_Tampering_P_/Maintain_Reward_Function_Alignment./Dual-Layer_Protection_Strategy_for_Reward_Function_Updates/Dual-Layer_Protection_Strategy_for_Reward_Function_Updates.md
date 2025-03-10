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

The paper's analysis reveals that maintaining reward function alignment during updates requires protecting both the update mechanism itself and ensuring the quality of the updates. This leads to a two-pronged strategy: first, securing the infrastructure through which updates occur, and second, ensuring the updates themselves maintain proper alignment with intended goals.

This breakdown is informed by the paper's formal analysis of uninfluenceable learning and time-inconsistency handling. The first sub-goal addresses the structural integrity of the update process, incorporating the paper's insights about privacy and protection of the update mechanism. The second sub-goal focuses on the semantic integrity of updates, drawing from the paper's analysis of direct learning and counterfactual updates to ensure updates maintain proper interpretation and alignment with intended goals.

### Order

1. Secure_Update_Infrastructure
2. Ensure_Update_Alignment
