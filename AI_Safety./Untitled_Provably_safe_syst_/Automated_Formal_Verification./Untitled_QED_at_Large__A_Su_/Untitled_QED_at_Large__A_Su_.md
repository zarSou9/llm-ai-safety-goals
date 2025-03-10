### Paper

```json
{
	"id": "https://arxiv.org/abs/2003.06458",
	"arxiv_id": "2003.06458",
	"url": "https://arxiv.org/abs/2003.06458",
	"title": "QED at Large: A Survey of Engineering of Formally Verified Software",
	"published_date": "2020-03-13T00:00:00.000Z",
	"abstract": "Development of formal proofs of correctness of programs can increase actual and perceived reliability and facilitate better understanding of program specifications and their underlying assumptions. Tools supporting such development have been available for over 40 years, but have only recently seen wide practical use. Projects based on construction of machine-checked formal proofs are now reaching an unprecedented scale, comparable to large software projects, which leads to new challenges in proof development and maintenance. Despite its increasing importance, the field of proof engineering is seldom considered in its own right; related theories, techniques, and tools span many fields and venues. This survey of the literature presents a holistic understanding of proof engineering for program correctness, covering impact in practice, foundations, proof automation, proof organization, and practical proof development.",
	"citation_count": 65,
	"influential_citation_count": 1,
	"ref": "17914"
}
```

### Explanation

The paper approaches automated formal verification through the lens of proof engineering - treating the development of formal proofs as a software engineering discipline. It emphasizes that proving properties of complex systems requires not just automated theorem proving capabilities, but also robust infrastructure for checking proofs, clear ways to specify properties, and principled methodologies for managing large proof developments.

The breakdown reflects the key technical components needed for automated verification of complex systems, as outlined in the paper's sections on foundations, automation, and proof organization. Automated theorem proving provides the core capability to discover proofs, while proof checking infrastructure ensures these proofs are trustworthy. Specification languages provide the formal framework for expressing what needs to be proved, while proof engineering methodology enables scaling these techniques to large systems.

These components work together as an integrated verification pipeline: Properties are expressed in specification languages, automated theorem provers attempt to find proofs of these properties, proof checkers verify the correctness of these proofs, and proof engineering methods help manage the overall development. The paper emphasizes that all of these aspects must scale together to handle AGI-scale systems - automated proving alone is insufficient without corresponding advances in specification, checking, and engineering practices. This holistic approach is critical for achieving automated verification that is both powerful enough to handle complex properties and reliable enough to trust for safety-critical AGI systems.

### Order

1. Automated_Theorem_Proving.
2. Proof_Checking_Infrastructure.
3. Specification_Language_Development.
4. Proof_Engineering_Methodology.
