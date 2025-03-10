### Paper

```json
{
	"id": "http://arxiv.org/abs/2401.13544",
	"arxiv_id": "2401.13544",
	"url": "http://arxiv.org/abs/2401.13544",
	"title": "Beyond Concept Bottleneck Models: How to Make Black Boxes Intervenable?",
	"published_date": "2024-01-24T00:00:00.000Z",
	"abstract": "Recently, interpretable machine learning has re-explored concept bottleneck models (CBM). An advantage of this model class is the user's ability to intervene on predicted concept values, affecting the downstream output. In this work, we introduce a method to perform such concept-based interventions on pretrained neural networks, which are not interpretable by design, only given a small validation set with concept labels. Furthermore, we formalise the notion of intervenability as a measure of the effectiveness of concept-based interventions and leverage this definition to fine-tune black boxes. Empirically, we explore the intervenability of black-box classifiers on synthetic tabular and natural image benchmarks. We focus on backbone architectures of varying complexity, from simple, fully connected neural nets to Stable Diffusion. We demonstrate that the proposed fine-tuning improves intervention effectiveness and often yields better-calibrated predictions. To showcase the practical utility of our techniques, we apply them to deep chest X-ray classifiers and show that fine-tuned black boxes are more intervenable than CBMs. Lastly, we establish that our methods are still effective under vision-language-model-based concept annotations, alleviating the need for a human-annotated validation set.",
	"citation_count": 8,
	"influential_citation_count": 0,
	"ref": "78403"
}
```

### Explanation

This paper presents a method for making black-box neural networks more interpretable and controllable by enabling interventions on internal concepts, even without being explicitly designed for interpretability, which relates to the sub-goal by offering a potential approach for making AI systems more transparent and verifiable while preserving their capabilities. However, the paper focuses on relatively simple classification tasks rather than extracting complete algorithms from complex AI systems.
