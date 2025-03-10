### Description

Ensure AI systems cannot achieve higher rewards by manipulating the information that feeds into reward calculations. This requires maintaining the intended relationship between the actual state of the world and the observations/inputs used to compute rewards.

### Questions

- How can we develop formal verification methods to prove that an AI system's observation channels maintain semantic consistency with ground truth, even as the system's capabilities increase?

- What architectural patterns or mechanisms could enable an AI system to detect its own potential reward input tampering attempts without creating new attack surfaces or compromising reward process privacy?

- How can we design reward input mechanisms that remain robust against tampering even when the AI system has a deeper understanding of physics and reality than was anticipated during system design?

- What mathematical frameworks could help us precisely characterize and measure the degree of 'causal faithfulness' between real-world states and their corresponding reward input representations?

- How can we develop adversarial testing approaches that effectively probe for subtle ways an AI system might manipulate reward inputs without triggering obvious red flags or detection mechanisms?

- What theoretical guarantees can we develop around the preservation of reward input integrity when an AI system is capable of creating or controlling other AI systems that could act as intermediaries?

- How can we design reward input mechanisms that remain robust against tampering even when operating in novel domains or environments not encountered during training or system development?
