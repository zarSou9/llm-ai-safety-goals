### Paper

```json
{
	"id": "https://arxiv.org/abs/2405.06624",
	"arxiv_id": "2405.06624",
	"url": "https://arxiv.org/abs/2405.06624",
	"title": "Towards Guaranteed Safe AI: A Framework for Ensuring Robust and Reliable AI Systems",
	"published_date": "2024-05-10T00:00:00.000Z",
	"abstract": "Ensuring that AI systems reliably and robustly avoid harmful or dangerous behaviours is a crucial challenge, especially for AI systems with a high degree of autonomy and general intelligence, or systems used in safety-critical contexts. In this paper, we will introduce and define a family of approaches to AI safety, which we will refer to as guaranteed safe (GS) AI. The core feature of these approaches is that they aim to produce AI systems which are equipped with high-assurance quantitative safety guarantees. This is achieved by the interplay of three core components: a world model (which provides a mathematical description of how the AI system affects the outside world), a safety specification (which is a mathematical description of what effects are acceptable), and a verifier (which provides an auditable proof certificate that the AI satisfies the safety specification relative to the world model). We outline a number of approaches for creating each of these three core components, describe the main technical challenges, and suggest a number of potential solutions to them. We also argue for the necessity of this approach to AI safety, and for the inadequacy of the main alternative approaches.",
	"citation_count": 32,
	"influential_citation_count": 4,
	"ref": "49492"
}
```

### Explanation

The paper presents safety properties along a spectrum from universal constraints to domain-specific requirements, suggesting a natural layered approach to defining core safety properties. This breakdown separates the fundamental mathematical properties that must hold universally to prevent catastrophic outcomes from the contextual properties needed for specific capabilities and use cases.

The strategy involves first establishing rigorous mathematical foundations for universal safety constraints, then developing frameworks for domain-specific requirements, and finally creating a comprehensive formalization framework that enables precise specification and composition of these properties. This approach ensures both theoretical completeness through fundamental properties and practical applicability through contextual properties, while the formalization framework provides the mathematical precision needed for verification.

### Order

1. Fundamental_Safety_Properties
2. Contextual_Safety_Properties
3. Safety_Property_Formalization_Framework
