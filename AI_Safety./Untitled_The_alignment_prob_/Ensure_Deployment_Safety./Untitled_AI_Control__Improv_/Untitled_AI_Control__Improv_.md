### Paper

```json
{
	"id": "https://arxiv.org/abs/2312.06942",
	"arxiv_id": "2312.06942",
	"url": "https://arxiv.org/abs/2312.06942",
	"title": "AI Control: Improving Safety Despite Intentional Subversion",
	"published_date": "2023-12-12T00:00:00.000Z",
	"abstract": "As large language models (LLMs) become more powerful and are deployed more autonomously, it will be increasingly important to prevent them from causing harmful outcomes. Researchers have investigated a variety of safety techniques for this purpose, e.g. using models to review the outputs of other models, or red-teaming techniques to surface subtle failure modes. However, researchers have not evaluated whether such techniques still ensure safety if the model is itself intentionally trying to subvert them. In this paper, we develop and evaluate pipelines of safety techniques (\"protocols\") that are robust to intentional subversion. We investigate a scenario in which we want to solve a sequence of programming problems, using access to a powerful but untrusted model (in our case, GPT-4), access to a less powerful trusted model (in our case, GPT-3.5), and limited access to high-quality trusted labor. We investigate protocols that aim to never submit solutions containing backdoors, which we operationalize here as logical errors that are not caught by test cases. We investigate a range of protocols and test each against strategies that the untrusted model could use to subvert them. One protocol is what we call trusted editing. This protocol first asks GPT-4 to write code, and then asks GPT-3.5 to rate the suspiciousness of that code. If the code is below some suspiciousness threshold, it is submitted. Otherwise, GPT-3.5 edits the solution to remove parts that seem suspicious and then submits the edited code. Another protocol is untrusted monitoring. This protocol asks GPT-4 to write code, and then asks another instance of GPT-4 whether the code is backdoored, using various techniques to prevent the GPT-4 instances from colluding. These protocols improve substantially on simple baselines.",
	"citation_count": 20,
	"influential_citation_count": 1,
	"ref": "03043"
}
```

### Explanation

This paper investigates safety protocols designed to prevent powerful AI models (like GPT-4) from intentionally causing harm when deployed to solve tasks, specifically by developing and testing methods that use less powerful trusted models to monitor and edit the outputs of more powerful but potentially untrustworthy models. This directly addresses the sub-goal of AI safety by exploring concrete mechanisms to maintain control over AI systems and prevent them from causing harm through intentional subversion.
