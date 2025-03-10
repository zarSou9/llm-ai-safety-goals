### Paper

```json
{
	"id": "https://arxiv.org/abs/2406.11240",
	"arxiv_id": "2406.11240",
	"url": "https://arxiv.org/abs/2406.11240",
	"title": "The Benefits of Power Regularization in Cooperative Reinforcement Learning",
	"published_date": "2024-06-17T00:00:00.000Z",
	"abstract": "Cooperative Multi-Agent Reinforcement Learning (MARL) algorithms, trained only to optimize task reward, can lead to a concentration of power where the failure or adversarial intent of a single agent could decimate the reward of every agent in the system. In the context of teams of people, it is often useful to explicitly consider how power is distributed to ensure no person becomes a single point of failure. Here, we argue that explicitly regularizing the concentration of power in cooperative RL systems can result in systems which are more robust to single agent failure, adversarial attacks, and incentive changes of co-players. To this end, we define a practical pairwise measure of power that captures the ability of any co-player to influence the ego agent's reward, and then propose a power-regularized objective which balances task reward and power concentration. Given this new objective, we show that there always exists an equilibrium where every agent is playing a power-regularized best-response balancing power and task reward. Moreover, we present two algorithms for training agents towards this power-regularized objective: Sample Based Power Regularization (SBPR), which injects adversarial data during training; and Power Regularization via Intrinsic Motivation (PRIM), which adds an intrinsic motivation to regulate power to the training objective. Our experiments demonstrate that both algorithms successfully balance task reward and power, leading to lower power behavior than the baseline of task-only reward and avoid catastrophic events in case an agent in the system goes off-policy.",
	"citation_count": 2,
	"influential_citation_count": 1,
	"ref": "93033"
}
```

### Explanation

This paper explores methods to prevent power concentration in multi-agent AI systems by introducing power regularization techniques that make the systems more robust against individual agent failures or misalignment, which directly addresses preventing power-seeking behavior as a key component of AI safety. The authors demonstrate that their approach successfully balances task performance with power distribution, making systems less vulnerable to catastrophic failures from single agents gaining too much control.
