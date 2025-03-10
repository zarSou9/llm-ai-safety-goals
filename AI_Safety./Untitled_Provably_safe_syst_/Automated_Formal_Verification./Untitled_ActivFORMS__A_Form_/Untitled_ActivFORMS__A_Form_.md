### Paper

```json
{
	"id": "https://arxiv.org/abs/1908.11179",
	"arxiv_id": "1908.11179",
	"url": "https://arxiv.org/abs/1908.11179",
	"title": "ActivFORMS: A Formally Founded Model-based Approach to Engineer Self-adaptive Systems",
	"published_date": "2019-08-29T00:00:00.000Z",
	"abstract": "Self-adaptation equips a computing system with a feedback loop that enables it to deal with change caused by uncertainties during operation, such as changing availability of resources and fluctuating workloads. To ensure that the system complies with the adaptation goals, recent research suggests the use of formal techniques at runtime. Yet, existing approaches have three limitations that affect their practical applicability: (i) they ignore correctness of the behavior of the feedback loop, (ii) they rely on exhaustive verification at runtime to select adaptation options to realize the adaptation goals, which is time- and resource-demanding, and (iii) they provide limited or no support for changing adaptation goals at runtime. To tackle these shortcomings, we present ActivFORMS (Active FORmal Models for Self-adaptation). ActivFORMS contributes an end-to-end approach for engineering self-adaptive systems, spanning four main stages of the life cycle of a feedback loop: design, deployment, runtime adaptation, and evolution. We also present ActivFORMS-ta, a tool-supported instance of ActivFORMS that leverages timed automata models and statistical model checking at runtime. We validate the research results using an IoT application for building security monitoring that is deployed in Leuven. The experimental results demonstrate that ActivFORMS supports correctness of the behavior of the feedback loop, achieves the adaptation goals in an efficient way, and supports changing adaptation goals at runtime.",
	"citation_count": 27,
	"influential_citation_count": 2,
	"ref": "49407"
}
```

### Explanation

This paper presents ActivFORMS, an approach for engineering self-adaptive systems that uses formal models and verification throughout the system lifecycle to ensure correctness of adaptive behavior, which is relevant to automated formal verification but focuses more narrowly on verifying self-adaptive systems rather than general AGI systems. The approach demonstrates formal verification techniques being successfully applied to runtime systems, though at a much smaller scale than would be needed for AGI verification.
