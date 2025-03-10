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

The paper suggests that effective automated theorem proving requires a balance between fully automated capabilities for simpler properties and semi-automated support for complex properties. Both of these must be built on robust infrastructure that ensures correctness and enables integration with broader verification workflows. This naturally suggests breaking down the goal based on these distinct but complementary capabilities needed for a complete automated theorem proving system. The approach separates core automated proving capabilities from interactive proving support, while ensuring both are built on shared infrastructure for proof checking and verification integration. This creates clear separation of concerns while maintaining cohesion through shared infrastructure.
