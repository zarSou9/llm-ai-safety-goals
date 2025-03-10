### Paper

```json
{
	"id": "https://arxiv.org/abs/2311.10538",
	"arxiv_id": "2311.10538",
	"url": "https://arxiv.org/abs/2311.10538",
	"title": "Testing Language Model Agents Safely in the Wild",
	"published_date": "2023-11-17T00:00:00.000Z",
	"abstract": "A prerequisite for safe autonomy-in-the-wild is safe testing-in-the-wild. Yet real-world autonomous tests face several unique safety challenges, both due to the possibility of causing harm during a test, as well as the risk of encountering new unsafe agent behavior through interactions with real-world and potentially malicious actors. We propose a framework for conducting safe autonomous agent tests on the open internet: agent actions are audited by a context-sensitive monitor that enforces a stringent safety boundary to stop an unsafe test, with suspect behavior ranked and logged to be examined by humans. We design a basic safety monitor (AgentMonitor) that is flexible enough to monitor existing LLM agents, and, using an adversarial simulated agent, we measure its ability to identify and stop unsafe situations. Then we apply the AgentMonitor on a battery of real-world tests of AutoGPT, and we identify several limitations and challenges that will face the creation of safe in-the-wild tests as autonomous agents grow more capable.",
	"citation_count": 16,
	"influential_citation_count": 2,
	"ref": "09740"
}
```

### Explanation

This paper proposes a monitoring framework to safely test autonomous AI agents in real-world environments by enforcing safety boundaries and logging suspicious behaviors, which directly addresses deployment safety risks by helping ensure AI systems maintain beneficial behavior outside of training conditions and preventing potential harm during testing.
