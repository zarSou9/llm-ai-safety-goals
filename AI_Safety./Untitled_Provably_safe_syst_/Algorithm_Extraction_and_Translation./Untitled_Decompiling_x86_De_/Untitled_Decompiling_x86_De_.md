### Paper

```json
{
	"id": "https://arxiv.org/abs/2210.01075",
	"arxiv_id": "2210.01075",
	"url": "https://arxiv.org/abs/2210.01075",
	"title": "Decompiling x86 Deep Neural Network Executables",
	"published_date": "2022-10-03T00:00:00.000Z",
	"abstract": "Due to their widespread use on heterogeneous hardware devices, deep learning (DL) models are compiled into executables by DL compilers to fully leverage low-level hardware primitives. This approach allows DL computations to be undertaken at low cost across a variety of computing platforms, including CPUs, GPUs, and various hardware accelerators. We present BTD (Bin to DNN), a decompiler for deep neural network (DNN) executables. BTD takes DNN executables and outputs full model specifications, including types of DNN operators, network topology, dimensions, and parameters that are (nearly) identical to those of the input models. BTD delivers a practical framework to process DNN executables compiled by different DL compilers and with full optimizations enabled on x86 platforms. It employs learning-based techniques to infer DNN operators, dynamic analysis to reveal network architectures, and symbolic execution to facilitate inferring dimensions and parameters of DNN operators. Our evaluation reveals that BTD enables accurate recovery of full specifications of complex DNNs with millions of parameters (e.g., ResNet). The recovered DNN specifications can be re-compiled into a new DNN executable exhibiting identical behavior to the input executable. We show that BTD can boost two representative attacks, adversarial example generation and knowledge stealing, against DNN executables. We also demonstrate cross-architecture legacy code reuse using BTD, and envision BTD being used for other critical downstream tasks like DNN security hardening and patching.",
	"citation_count": 10,
	"influential_citation_count": 1,
	"ref": "16080"
}
```

### Explanation

This paper presents BTD, a tool for decompiling neural network executables back into their original model specifications, which directly supports the sub-goal by demonstrating a method to make black-box AI systems (in executable form) more transparent and analyzable by extracting their underlying neural network architecture and parameters.
