### Paper

```json
{
	"id": "https://arxiv.org/abs/2011.08596",
	"arxiv_id": "2011.08596",
	"url": "https://arxiv.org/abs/2011.08596",
	"title": "Learning outside the Black-Box: The pursuit of interpretable models",
	"published_date": "2020-11-17T00:00:00.000Z",
	"abstract": "Machine Learning has proved its ability to produce accurate models but the deployment of these models outside the machine learning community has been hindered by the difficulties of interpreting these models. This paper proposes an algorithm that produces a continuous global interpretation of any given continuous black-box function. Our algorithm employs a variation of projection pursuit in which the ridge functions are chosen to be Meijer G-functions, rather than the usual polynomial splines. Because Meijer G-functions are differentiable in their parameters, we can tune the parameters of the representation by gradient descent; as a consequence, our algorithm is efficient. Using five familiar data sets from the UCI repository and two familiar machine learning algorithms, we demonstrate that our algorithm produces global interpretations that are both highly accurate and parsimonious (involve a small number of terms). Our interpretations permit easy understanding of the relative importance of features and feature interactions. Our interpretation algorithm represents a leap forward from the previous state of the art.",
	"citation_count": 24,
	"influential_citation_count": 3,
	"ref": "09352"
}
```

### Explanation

This paper presents an algorithm that can convert complex black-box machine learning models into more interpretable mathematical representations using Meijer G-functions, which could be a stepping stone toward extracting and translating AI systems into verifiable code, though it focuses primarily on interpretation rather than formal verification or safety guarantees.
