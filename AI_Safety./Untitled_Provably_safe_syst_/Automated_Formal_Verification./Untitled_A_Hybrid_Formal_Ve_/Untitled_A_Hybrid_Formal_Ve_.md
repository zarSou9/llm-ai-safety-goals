### Paper

```json
{
	"id": "https://arxiv.org/abs/1902.08726",
	"arxiv_id": "1902.08726",
	"url": "https://arxiv.org/abs/1902.08726",
	"title": "A Hybrid Formal Verification System in Coq for Ensuring the Reliability and Security of Ethereum-Based Service Smart Contracts",
	"published_date": "2019-02-23T00:00:00.000Z",
	"abstract": "This paper reports a formal symbolic process virtual machine (FSPVM) denoted as FSPVM-E for verifying the reliability and security of Ethereum-based services at the source code level of smart contracts. A Coq proof assistant is employed for programming the system and for proving its correctness. The current version of FSPVM-E adopts execution-verification isomorphism, which is an application extension of Curry-Howard isomorphism, as its fundamental theoretical framework to combine symbolic execution and higher-order logic theorem proving. The four primary components of FSPVM-E include a general, extensible, and reusable formal memory framework, an extensible and universal formal intermediate programming language denoted as Lolisa, which is a large subset of the Solidity programming language using generalized algebraic datatypes, the corresponding formally verified interpreter of Lolisa, denoted as FEther, and assistant tools and libraries. The self-correctness of all components is certified in Coq. FSPVM-E supports the ERC20 token standard, and can automatically and symbolically execute Ethereum-based smart contracts, scan their standard vulnerabilities, and verify their reliability and security properties with Hoare-style logic in Coq.",
	"citation_count": 23,
	"influential_citation_count": 0,
	"ref": "46920"
}
```

### Explanation

This paper presents a formal verification system built in Coq that can automatically verify security properties of Ethereum smart contracts through a combination of symbolic execution and theorem proving. While this demonstrates progress in automated formal verification of complex software systems, it focuses specifically on smart contracts rather than the broader scale and complexity needed for AGI systems.
