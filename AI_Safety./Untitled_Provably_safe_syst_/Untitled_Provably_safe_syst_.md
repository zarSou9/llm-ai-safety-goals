### Paper

```json
{
	"url": "https://arxiv.org/abs/2309.01933",
	"arxiv_id": "2309.01933",
	"title": "Provably safe systems: the only path to controllable AGI",
	"abstract": "We describe a path to humanity safely thriving with powerful Artificial General Intelligences (AGIs) by building them to provably satisfy human-specified requirements. We argue that this will soon be technically feasible using advanced AI for formal verification and mechanistic interpretability. We further argue that it is the only path which guarantees safe controlled AGI. We end with a list of challenge problems whose solution would contribute to this positive outcome and invite readers to join in this work.",
	"published_date": "2023-09-05T00:00:00",
	"citation_count": 14,
	"influential_citation_count": 0
}
```

### Explanation

The paper proposes that the only reliable path to safe AGI is through provably secure systems, where both AI software and the hardware it runs on must mathematically demonstrate compliance with formal safety specifications before being allowed to operate. Rather than trying to align black-box neural networks through training or hoping that safety emerges from testing, this approach requires that every deployed AI system carry mathematical proofs that it cannot violate critical safety constraints. This creates multiple layers of protection: the AI systems themselves must be provably safe, the hardware they run on must enforce these proofs, and the entire infrastructure must be designed to prevent circumvention.

The five identified sub-goals form an interlocking system where each component reinforces the others. Automated formal verification provides the core mathematical foundation for proving safety properties, but this capability alone is insufficient without comprehensive safety specifications that define what must be proven. These specifications in turn rely on algorithm extraction methods to translate powerful AI capabilities into a form that can be verified. The resulting provably safe systems can only be trusted if they run on secure hardware infrastructure that enforces compliance checking. Finally, the governance and enforcement framework ensures universal adoption of these technical safeguards, preventing any individual actor from deploying unverified systems that could pose existential risks.

This integrated approach addresses the AGI safety challenge by creating multiple complementary barriers against catastrophic outcomes. Even if a superintelligent system tried to circumvent safety constraints, it would need to simultaneously defeat the mathematical proofs of its limitations, compromise tamper-proof hardware, and evade detection by the verification infrastructure. By requiring proofs rather than just testing or training, the system provides guarantees rather than mere empirical evidence of safety. The governance layer ensures these protections are universally adopted, while the hardware infrastructure makes compliance physically mandatory rather than just legally required. Together, these components create a robust framework where safety is enforced through multiple independent mechanisms, making it extremely difficult for even a superintelligent system to cause catastrophic harm.

### Order

1. Automated_Formal_Verification.
2. Safe_Hardware_Infrastructure.
3. Safety_Specifications.
4. Algorithm_Extraction_and_Translation.
5. Governance_and_Enforcement.
