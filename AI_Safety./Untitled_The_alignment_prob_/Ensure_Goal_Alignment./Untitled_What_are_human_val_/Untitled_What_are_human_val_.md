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

The paper approaches goal alignment through a novel framework centered on properly understanding, eliciting, and reconciling human values. Rather than treating alignment as simply a technical optimization problem, it presents it as a challenge requiring both philosophical clarity about human values and practical mechanisms for capturing and implementing them. The paper's key insight is that successful alignment requires values to be fine-grained, legitimate, robust, and generalizable.

The breakdown reflects the paper's core components while organizing them into distinct challenges that must be addressed. The first two sub-goals focus on the fundamental requirements of properly capturing human values (through elicitation) and combining them effectively (through reconciliation). These form the foundation for alignment by ensuring we have the right target to align to. The third sub-goal addresses the critical challenge of generalization, which the paper identifies as essential for maintaining alignment beyond training scenarios. The fourth sub-goal captures the paper's emphasis on legitimacy and oversight, which it argues are necessary for any alignment solution to be trusted and effective in practice.

These sub-goals work together in a hierarchical way: proper value elicitation provides the raw material that the reconciliation system must work with, while generalization ensures these reconciled values can guide behavior in new situations, and the oversight process ensures the whole system maintains legitimacy and effectiveness over time. This structure reflects the paper's argument that successful alignment requires both getting the technical components right (elicitation, reconciliation, generalization) and ensuring the social/institutional components (legitimacy, oversight, trust) are properly addressed.

### Order

1. Establish_Value_Elicitation_Framework.
2. Develop_Value_Reconciliation_System.
3. Ensure_Value_Generalization.
4. Create_Legitimate_Oversight_Process.
