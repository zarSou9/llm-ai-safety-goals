### Paper

```json
{
	"id": "https://arxiv.org/pdf/1712.01785.pdf",
	"arxiv_id": "1712.01785",
	"url": "https://arxiv.org/pdf/1712.01785.pdf",
	"title": "Towards Practical Verification of Machine Learning: The Case of Computer Vision Systems",
	"published_date": "2023-11-15T00:00:00.000Z",
	"abstract": "Due to the increasing usage of machine learning (ML) techniques in security- and safety-critical domains, such as autonomous systems and medical diagnosis, ensuring correct behavior of ML systems, especially for different corner cases, is of growing importance. In this paper, we propose a generic framework for evaluating security and robustness of ML systems using different real-world safety properties. We further design, implement and evaluate VeriVis, a scalable methodology that can verify a diverse set of safety properties for state-of-the-art computer vision systems with only blackbox access. VeriVis leverage different input space reduction techniques for efficient verification of different safety properties. VeriVis is able to find thousands of safety violations in fifteen state-of-the-art computer vision systems including ten Deep Neural Networks (DNNs) such as Inception-v3 and Nvidia's Dave self-driving system with thousands of neurons as well as five commercial third-party vision APIs including Google vision and Clarifai for twelve different safety properties. Furthermore, VeriVis can successfully verify local safety properties, on average, for around 31.7% of the test images. VeriVis finds up to 64.8x more violations than existing gradient-based methods that, unlike VeriVis, cannot ensure non-existence of any violations. Finally, we show that retraining using the safety violations detected by VeriVis can reduce the average number of violations up to 60.2%.",
	"citation_count": 101,
	"influential_citation_count": 6,
	"ref": "84295"
}
```

### Explanation

This paper presents VeriVis, a framework for verifying safety properties of computer vision systems by finding potential violations and corner cases where the systems might fail, which is relevant to AI safety as it provides practical methods for testing and improving the reliability of AI systems before deployment. While the paper focuses on current-generation ML systems rather than highly agentic AI, its verification approaches could inform methods for testing alignment and safety properties of more advanced systems.
