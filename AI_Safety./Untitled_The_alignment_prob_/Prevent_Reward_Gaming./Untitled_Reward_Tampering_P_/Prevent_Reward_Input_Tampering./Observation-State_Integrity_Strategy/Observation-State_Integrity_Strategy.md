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

The paper demonstrates that RF-input tampering occurs when an agent manipulates the relationship between task-relevant features of the world state and the observations used to compute rewards. To prevent this, we need both a defensive and a robust approach. First, we must maintain the integrity of the observation channel itself, ensuring observations accurately reflect relevant aspects of the world state within their intended range of variation. Second, we need reward mechanisms that remain robust even if observations are compromised, by basing rewards on reliable indicators of actual task completion rather than apparent observations.

This two-pronged strategy is supported by the paper's formal analysis using POMDPs with modifiable RF-inputs. The paper shows that while we can try to prevent observation tampering directly, we also need reward mechanisms (like history-based or belief-based rewards) that remain reliable even when observations are compromised. These approaches are complementary - maintaining observation integrity makes it easier to design robust reward mechanisms, while robust reward mechanisms provide a safety net when observation integrity is compromised.

### Order

1. Maintain_Observation_Channel_Integrity
2. Implement_Manipulation-Resistant_Reward_Processing
