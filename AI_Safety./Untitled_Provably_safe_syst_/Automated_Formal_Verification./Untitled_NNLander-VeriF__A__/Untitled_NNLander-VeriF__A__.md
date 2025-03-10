### Paper

```json
{
	"id": "https://arxiv.org/abs/2203.15841",
	"arxiv_id": "2203.15841",
	"url": "https://arxiv.org/abs/2203.15841",
	"title": "NNLander-VeriF: A Neural Network Formal Verification Framework for Vision-Based Autonomous Aircraft Landing",
	"published_date": "2022-03-29T00:00:00.000Z",
	"abstract": ". In this paper, we consider the problem of formally verifying a Neural Network (NN) based autonomous landing system. In such a system, a NN controller processes images from a camera to guide the aircraft while approaching the runway. A central challenge for the safety and liveness verification of vision-based closed-loop systems is the lack of mathematical models that captures the relation between the system states (e.g., position of the aircraft) and the images processed by the vision-based NN controller. Another challenge is the limited abilities of state-of-the-art NN model checkers. Such model checkers can reason only about simple input-output robustness properties of neural networks. This limitation creates a gap between the NN model checker abilities and the need to verify a closed-loop system while considering the aircraft dynamics, the perception components, and the NN controller. To this end, this paper presents NNLander-VeriF, a framework to verify vision-based NN controllers used for autonomous landing. NNLander-VeriF addresses the challenges above by exploiting geometric models of perspective cameras to obtain a mathematical model that captures the relation between the aircraft states and the inputs to the NN controller. By converting this model into a NN (with manually assigned weights) and composing it with the NN controller, one can capture the relation between aircraft states and control actions using one augmented NN. Such an augmented NN model leads to a natural encoding of the closed-loop verification into several NN robustness queries, which state-of-the-art NN model checkers can handle. Finally, we evaluate our framework to formally verify the properties of a trained NN and we show its efficiency. LiDAR scanners and cameras. These data",
	"citation_count": 22,
	"influential_citation_count": 1,
	"ref": "03861"
}
```

### Explanation

This paper presents a framework (NNLander-VeriF) for formally verifying neural network-based autonomous aircraft landing systems by converting geometric camera models into neural networks that can be combined with the control network, enabling verification of the complete closed-loop system using existing neural network verification tools. This work demonstrates progress on automated formal verification of complex AI systems, though at a more limited scale than would be needed for AGI systems.
