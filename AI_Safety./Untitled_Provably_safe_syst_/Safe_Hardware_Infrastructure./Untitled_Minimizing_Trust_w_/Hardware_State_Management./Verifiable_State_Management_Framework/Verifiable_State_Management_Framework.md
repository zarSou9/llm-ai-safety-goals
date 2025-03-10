### Paper

```json
{
	"id": "https://arxiv.org/abs/2203.08284",
	"arxiv_id": "2203.08284",
	"url": "https://arxiv.org/abs/2203.08284",
	"title": "Minimizing Trust with Exclusively-Used Physically-Isolated Hardware",
	"published_date": "2022-03-15T00:00:00.000Z",
	"abstract": "Smartphone owners often need to run security-critical programs on the same device as other untrusted and potentially malicious programs. This requires users to trust hardware and system software to correctly sandbox malicious programs, trust that is often misplaced. Our goal is to minimize the number and complexity of hardware and software components that a smartphone owner needs to trust to withstand adversarial inputs. We present a multi-domain hardware design composed of statically-partitioned, physically-isolated trust domains. We introduce a few simple, formally-verified hardware components to enable a program to gain provably exclusive and simultaneous access to both computation and I/O on a temporary basis. To manage this hardware, we present OctopOS, an OS composed of mutually distrustful subsystems. We present a prototype of this machine (hardware and OS) on a CPU-FPGA board and show that it incurs a small hardware cost compared to modern SoCs. For security-critical programs, we show that this machine significantly reduces the required trust compared to mainstream TEEs while achieving decent performance. For normal programs, performance is similar to a legacy machine.",
	"citation_count": 0,
	"influential_citation_count": 0,
	"ref": "78473"
}
```

### Explanation

The paper demonstrates that hardware state management requires both mechanisms for cleaning states and systems for verifying those states are truly clean. This suggests a two-pronged approach: first establishing formal definitions and specifications for what constitutes clean states across different hardware components, then implementing both the mechanisms to achieve those states and the systems to verify them.

The breakdown follows this pattern by first focusing on formal specification of clean states and verification requirements, then addressing the actual mechanisms for state cleaning and verification, and finally handling the secure transitioning between states. This creates a complete framework where states are well-defined, verifiably achievable, and securely maintained through transitions. The approach is informed by the paper's emphasis on provable exclusive access but extends beyond their specific implementation to create a more general framework for hardware state management.

### Order

1. Clean_State_Specification
2. State_Reset_Mechanisms
3. Secure_State_Transitions
