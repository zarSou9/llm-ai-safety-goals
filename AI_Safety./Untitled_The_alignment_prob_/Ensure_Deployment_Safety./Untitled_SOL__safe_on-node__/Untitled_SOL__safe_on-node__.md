### Paper

```json
{
	"id": "https://arxiv.org/pdf/2201.10477v1.pdf",
	"arxiv_id": "2201.10477",
	"url": "https://arxiv.org/pdf/2201.10477v1.pdf",
	"title": "SOL: safe on-node learning in cloud platforms",
	"published_date": "2022-01-25T00:00:00.000Z",
	"abstract": "Cloud platforms run many software agents on each server node. These agents manage all aspects of node operation, and in some cases frequently collect data and make decisions. Unfortunately, their behavior is typically based on pre-defined static heuristics or offline analysis; they do not leverage on-node machine learning (ML). In this paper, we first characterize the spectrum of node agents in Azure, and identify the classes of agents that are most likely to benefit from on-node ML. We then propose SOL, an extensible framework for designing ML-based agents that are safe and robust to the range of failure conditions that occur in production. SOL provides a simple API to agent developers and manages the scheduling and running of the agent-specific functions they write. We illustrate the use of SOL by implementing three ML-based agents that manage CPU cores, node power, and memory placement. Our experiments show that (1) ML substantially improves our agents, and (2) SOL ensures that agents operate safely under a variety of failure conditions. We conclude that ML-based agents show significant potential and that SOL can help build them.",
	"citation_count": 13,
	"influential_citation_count": 3,
	"ref": "78316"
}
```

### Explanation

This paper focuses on creating a framework for safely implementing machine learning agents in cloud computing environments, with emphasis on ensuring robustness against failures - while relevant to AI safety, it primarily addresses narrow AI systems in specific cloud computing contexts rather than the broader existential risks from agentic AI systems that could lead to loss of human control.
