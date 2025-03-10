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

Following the paper's framework around trusted bases and the de Bruijn criterion, this breakdown organizes proof checking infrastructure development into three fundamental challenges that must be addressed. The first focuses on developing the minimal trusted core that gives confidence in the overall system. The second addresses how to represent and process proofs efficiently at scale. The third ensures the infrastructure integrates effectively with the broader verification ecosystem.

This approach is informed by the paper's analysis of trusted computing bases and proof objects, particularly sections 4.3-4.4. By separating core checker correctness from proof representation and processing concerns, we can minimize the trusted base while still enabling practical verification at scale. The integration component ensures these theoretical advances translate to practical impact.
