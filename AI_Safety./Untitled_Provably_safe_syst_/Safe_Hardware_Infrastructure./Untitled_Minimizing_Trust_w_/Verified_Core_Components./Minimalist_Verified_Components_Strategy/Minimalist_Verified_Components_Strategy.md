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

The paper demonstrates that creating verified core components requires carefully balancing three key aspects: identifying the minimal set of required components, ensuring each component is simple enough to be verifiable, and proving their correctness through formal verification. This approach recognizes that the more components that must be trusted and the more complex each component is, the harder verification becomes and the more likely security vulnerabilities will exist.

The breakdown follows this insight by first determining the minimal set of components needed to enforce critical security properties, then designing these components to be as simple as possible while still providing required functionality, and finally proving their correctness through formal verification. This systematic approach ensures we achieve both minimal trust and verifiable security.

### Order

1. Security_Property_Analysis
2. Verifiable_Component_Design
3. Formal_Verification_Framework
