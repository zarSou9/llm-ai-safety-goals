### Paper

```json
{
	"id": "https://arxiv.org/abs/2312.01249",
	"arxiv_id": "2312.01249",
	"url": "https://arxiv.org/abs/2312.01249",
	"title": "A Multifidelity Sim-to-Real Pipeline for Verifiable and Compositional Reinforcement Learning",
	"published_date": "2023-12-02T00:00:00.000Z",
	"abstract": "We propose and demonstrate a compositional framework for training and verifying reinforcement learning (RL) systems within a multifidelity sim-to-real pipeline, in order to deploy reliable and adaptable RL policies on physical hardware. By decomposing complex robotic tasks into component subtasks and defining mathematical interfaces between them, the framework allows for the independent training and testing of the corresponding subtask policies, while simultaneously providing guarantees on the overall behavior that results from their composition. By verifying the performance of these subtask policies using a multifidelity simulation pipeline, the framework not only allows for efficient RL training, but also for a refinement of the subtasks and their interfaces in response to challenges arising from discrepancies between simulation and reality. In an experimental case study, we apply the framework to train and deploy a compositional RL system that successfully pilots a Warthog unmanned ground robot.",
	"citation_count": 0,
	"influential_citation_count": 0,
	"ref": "96369"
}
```

### Explanation

This paper presents a framework for safely training and verifying reinforcement learning systems by breaking down complex tasks into verifiable subtasks and using multi-fidelity simulation before real-world deployment, which is relevant to AI safety by providing a systematic approach to ensure AI systems maintain their intended behavior when moving from training to deployment conditions.
