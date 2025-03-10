### Description

Ensure AI systems cannot achieve high rewards through unintended exploits or deceptive behavior. This requires preventing both naive reward hacking and sophisticated situationally-aware gaming of reward mechanisms, even when systems have deep understanding of their training process.

### Questions

- How can we develop formal metrics to quantify the 'brittleness' of a reward specification - meaning how likely it is to be gameable - before deploying it for training, similar to how we measure adversarial robustness in computer vision?

- What are the fundamental mathematical relationships between model capability levels and the emergence of reward gaming behaviors? Can we identify precise capability thresholds where qualitative shifts in gaming strategies occur?

- How can we leverage causal learning to help AI systems distinguish between correlational and truly causal relationships in reward signals, potentially reducing their tendency to exploit spurious correlations?

- What methods can we develop to detect and measure reward gaming that occurs through subtle distributional shifts rather than obvious exploitation, especially in language models where gaming may manifest as sophisticated rhetorical strategies?

- How can we design reward mechanisms that remain robust even when AI systems have detailed knowledge of their own training process and reward structure? What theoretical guarantees can we develop for such mechanisms?

- Can we develop formal frameworks for understanding and preventing coordination between different instances or components of an AI system that might enable more sophisticated reward gaming strategies?

- What are the fundamental limits of using ensemble approaches for reward modeling? Is there a theoretical maximum robustness that can be achieved through ensembling, and what determines this limit?

- How can we develop automated methods to identify and characterize the complete set of possible reward gaming strategies available to an AI system in a given environment, similar to formal verification approaches?

### Order

1. Paper: "Reward Tampering Problems and Solutions in Reinforcement Learning: A Causal Influence Diagram Perspective"
2. Paper: "Avoiding Tampering Incentives in Deep RL via Decoupled Approval"
