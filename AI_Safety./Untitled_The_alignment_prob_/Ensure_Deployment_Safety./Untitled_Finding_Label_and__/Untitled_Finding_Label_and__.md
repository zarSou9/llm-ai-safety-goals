### Paper

```json
{
	"id": "https://arxiv.org/abs/2201.05797",
	"arxiv_id": "2201.05797",
	"url": "https://arxiv.org/abs/2201.05797",
	"title": "Finding Label and Model Errors in Perception Data With Learned Observation Assertions",
	"published_date": "2023-02-06T00:00:00.000Z",
	"abstract": "ML is being deployed in complex, real-world scenarios where errors have impactful consequences. In these systems, thorough testing of the ML pipelines is critical. A key component in ML deployment pipelines is the curation of labeled training data. Common practice in the ML literature assumes that labels are the ground truth. However, in our experience in a large autonomous vehicle development center, we have found that vendors can often provide erroneous labels, which can lead to downstream safety risks in trained models. To address these issues, we propose a new abstraction, learned observation assertions, and implement it in a system called Fixy. Fixy leverages existing organizational resources, such as existing (possibly noisy) labeled datasets or previously trained ML models, to learn a probabilistic model for finding errors in human- or model-generated labels. Given user-provided features and these existing resources, Fixy learns feature distributions that specify likely and unlikely values (e.g., that a speed of 30mph is likely but 300mph is unlikely). It then uses these feature distributions to score labels for potential errors. We show that Fixy can automatically rank potential errors in real datasets with up to 2x higher precision compared to recent work on model assertions and standard techniques such as uncertainty sampling. Furthermore, Fixy can uncover labeling errors in 70% of scenes in a popular autonomous vehicle dataset.",
	"citation_count": 16,
	"influential_citation_count": 0,
	"ref": "59869"
}
```

### Explanation

This paper presents Fixy, a system that helps detect errors in training data labels and model outputs by learning what observations are likely vs unlikely, which is relevant to AI safety by helping ensure ML systems are trained on accurate data and behave reliably. While valuable for improving ML system reliability, this work appears more focused on near-term safety in specific applications like autonomous vehicles rather than directly addressing existential risks from advanced AI systems.
