### Paper

```json
{
	"id": "https://arxiv.org/pdf/2008.11632v2.pdf",
	"arxiv_id": "2008.11632",
	"url": "https://arxiv.org/pdf/2008.11632v2.pdf",
	"title": "GuardNN: secure accelerator architecture for privacy-preserving deep learning",
	"published_date": "2022-07-10T00:00:00.000Z",
	"abstract": "This paper proposes GuardNN, a secure DNN accelerator that provides hardware-based protection for user data and model parameters even in an untrusted environment. GuardNN shows that the architecture and protection can be customized for a specific application to provide strong confidentiality and integrity guarantees with negligible overhead. The design of the GuardNN instruction set reduces the TCB to just the accelerator and allows confidentiality protection even when the instructions from a host cannot be trusted. GuardNN minimizes the overhead of memory encryption and integrity verification by customizing the off-chip memory protection for the known memory access patterns of a DNN accelerator. GuardNN is prototyped on an FPGA, demonstrating effective confidentiality protection with ~3% performance overhead for inference.",
	"citation_count": 22,
	"influential_citation_count": 6,
	"ref": "01184"
}
```

### Explanation

This paper presents GuardNN, a secure hardware accelerator architecture for deep neural networks that aims to protect both data and model parameters through hardware-based security mechanisms, demonstrating minimal performance overhead. While this work shows progress in securing AI hardware components, it focuses primarily on privacy and integrity protection rather than enforcing safety constraints or achieving tamper-proof security against superintelligent systems as required by the sub-goal.
