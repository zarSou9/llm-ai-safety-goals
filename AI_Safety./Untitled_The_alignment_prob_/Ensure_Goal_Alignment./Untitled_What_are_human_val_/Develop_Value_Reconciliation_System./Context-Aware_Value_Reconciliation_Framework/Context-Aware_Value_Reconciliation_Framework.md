### Paper

```json
{
	"id": "https://arxiv.org/abs/2404.10636",
	"arxiv_id": "2404.10636",
	"url": "https://arxiv.org/abs/2404.10636",
	"title": "What are human values, and how do we align AI to them?",
	"published_date": "2024-03-27T00:00:00.000Z",
	"abstract": "There is an emerging consensus that we need to align AI systems with human values (Gabriel, 2020; Ji et al., 2024), but it remains unclear how to apply this to language models in practice. We split the problem of\"aligning to human values\"into three parts: first, eliciting values from people; second, reconciling those values into an alignment target for training ML models; and third, actually training the model. In this paper, we focus on the first two parts, and ask the question: what are\"good\"ways to synthesize diverse human inputs about values into a target for aligning language models? To answer this question, we first define a set of 6 criteria that we believe must be satisfied for an alignment target to shape model behavior in accordance with human values. We then propose a process for eliciting and reconciling values called Moral Graph Elicitation (MGE), which uses a large language model to interview participants about their values in particular contexts; our approach is inspired by the philosophy of values advanced by Taylor (1977), Chang (2004), and others. We trial MGE with a representative sample of 500 Americans, on 3 intentionally divisive prompts (e.g. advice about abortion). Our results demonstrate that MGE is promising for improving model alignment across all 6 criteria. For example, almost all participants (89.1%) felt well represented by the process, and (89%) thought the final moral graph was fair, even if their value wasn't voted as the wisest. Our process often results in\"expert\"values (e.g. values from women who have solicited abortion advice) rising to the top of the moral graph, without defining who is considered an expert in advance.",
	"citation_count": 11,
	"influential_citation_count": 0,
	"ref": "79076"
}
```

### Explanation

The paper's Moral Graph Elicitation process demonstrates that effective value reconciliation requires three key components: concrete value representation, contextual understanding, and mechanisms for legitimate reconciliation. This breakdown adapts these insights into a general framework where values are first made concrete and actionable, then mapped to relevant contexts, and finally reconciled through legitimate processes that preserve wisdom and expertise. The approach emphasizes the paper's finding that value conflicts often arise from insufficient context specification or imprecise value representation, rather than true philosophical incompatibility. By addressing these components systematically, we can create a robust system for determining which values should guide AI behavior in different situations.

### Order

1. Establish_Value_Representation_System
2. Develop_Context_Mapping_Framework
3. Create_Value_Reconciliation_Mechanism
