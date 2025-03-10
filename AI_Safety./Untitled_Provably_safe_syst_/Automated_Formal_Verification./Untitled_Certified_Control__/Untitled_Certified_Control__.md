### Paper

```json
{
	"id": "https://arxiv.org/abs/2104.06178",
	"arxiv_id": "2104.06178",
	"url": "https://arxiv.org/abs/2104.06178",
	"title": "Certified Control: An Architecture for Verifiable Safety of Autonomous Vehicles",
	"published_date": "2021-03-29T00:00:00.000Z",
	"abstract": "Widespread adoption of autonomous cars will require greater confidence in their safety than is currently possible. Certified control is a new safety architecture whose goal is two-fold: to achieve a very high level of safety, and to provide a framework for justifiable confidence in that safety. The key idea is a runtime monitor that acts, along with sensor hardware and low-level control and actuators, as a small trusted base, ensuring the safety of the system as a whole. Unfortunately, in current systems complex perception makes the verification even of a runtime monitor challenging. Unlike traditional runtime monitoring, therefore, a certified control monitor does not perform perception and analysis itself. Instead, the main controller assembles evidence that the proposed action is safe into a certificate that is then checked independently by the monitor. This exploits the classic gap between the costs of finding and checking. The controller is assigned the task of finding the certificate, and can thus use the most sophisticated algorithms available (including learning-enabled software); the monitor is assigned only the task of checking, and can thus run quickly and be smaller and formally verifiable. This paper explains the key ideas of certified control and illustrates them with a certificate for LiDAR data and its formal verification. It shows how the architecture dramatically reduces the amount of code to be verified, providing an end-to-end safety analysis that would likely not be achievable in a traditional architecture.",
	"citation_count": 5,
	"influential_citation_count": 2,
	"ref": "24955"
}
```

### Explanation

This paper proposes a "certified control" architecture where a formally verifiable runtime monitor checks safety certificates produced by the main controller of an autonomous vehicle, allowing complex perception and control systems to be safely deployed without having to formally verify the entire system. This approach is relevant to automated formal verification by demonstrating how to make formal verification more tractable by strategically verifying only a small trusted component rather than an entire complex system.
