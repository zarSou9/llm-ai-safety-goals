### Description

Create and verify the minimal set of core hardware components that must be trusted for the system's security properties to hold. These components must be simple enough to be formally verified while being powerful enough to enforce critical security properties.

### Questions

- What are the fundamental mathematical properties that define the minimal set of operations needed to enforce security invariants in hardware, and how can we prove these are both necessary and sufficient?

- How can we develop verification techniques that scale to handle the interaction effects between multiple verified components while maintaining tractable proof complexity?

- What novel circuit-level primitives could enable simpler verification of security properties while still providing sufficient computational power for enforcing safety constraints?

- How can we formally characterize and verify the information flow properties of hardware components across power cycles and reset states to ensure true isolation between uses?

- What are the minimal requirements for a verified hardware root of trust that can bootstrap trust in larger verified components while remaining simple enough to formally verify?

- How can we develop compositional verification approaches that allow verified core components to be safely combined into larger systems while preserving their security properties?

- What novel hardware architectures could enable formal verification of timing-sensitive security properties without requiring complex timing models in the verification process?

- How can we create provably correct hardware mechanisms for secure state transition that are simple enough to verify but powerful enough to support practical safety enforcement?
