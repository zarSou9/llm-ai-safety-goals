### Paper

```json
{
	"id": "https://arxiv.org/abs/2406.11779",
	"arxiv_id": "2406.11779",
	"url": "https://arxiv.org/abs/2406.11779",
	"title": "Compact Proofs of Model Performance via Mechanistic Interpretability",
	"published_date": "2024-06-17T00:00:00.000Z",
	"abstract": "We propose using mechanistic interpretability -- techniques for reverse engineering model weights into human-interpretable algorithms -- to derive and compactly prove formal guarantees on model performance. We prototype this approach by formally proving accuracy lower bounds for a small transformer trained on Max-of-K, validating proof transferability across 151 random seeds and four values of K. We create 102 different computer-assisted proof strategies and assess their length and tightness of bound on each of our models. Using quantitative metrics, we find that shorter proofs seem to require and provide more mechanistic understanding. Moreover, we find that more faithful mechanistic understanding leads to tighter performance bounds. We confirm these connections by qualitatively examining a subset of our proofs. Finally, we identify compounding structureless errors as a key challenge for using mechanistic interpretability to generate compact proofs on model performance.",
	"citation_count": 4,
	"influential_citation_count": 0,
	"ref": "26994"
}
```

### Explanation

This paper explores using mechanistic interpretability to reverse-engineer neural networks into human-understandable algorithms and generate formal proofs of their behavior, demonstrating this approach on a small transformer model and analyzing how proof quality relates to mechanistic understanding - directly addressing the sub-goal of converting black-box AI systems into verifiable code.
