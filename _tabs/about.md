---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

Hi 👋 I am Wanchao, welcome to my blog. I'm a Software Engineer working on building large scale distributed training infrastructure to power Large Language Models (LLMs). I worked at PyTorch Core @ Meta and maintains the [torch.distributed](https://pytorch.org/docs/stable/distributed.html) module. I completed my master degree at Carnegie Mellon University and bachelor degree at Shanghai Jiaotong Univeristy.

My research interests include large scale training systems, optimization on training/inference efficiencies for LLM and AI models. You might know me for a couple of my recent works in the large scale training field:

* I authored [torch.distributed.tensor](https://pytorch.org/docs/stable/distributed.tensor.html) (DTensor), which provides a fundamental tensor sharding primitive to the PyTorch distributed training framework. PyTorch DTensor is powering a wide range of PyTorch native parallelism solutions, including FSDP2, TP, CP, etc.
* I am the main author of [TorchTitan](https://github.com/pytorch/torchtitan), a PyTorch native large scale training library for the generative AI models. TorchTitan incorporates PyTorch native multi-dimensional parallelisms (FSDP2, TP, CP, PP), compiler accelarations (torch.compile), mixed precision training, (i.e. Float8), fault tolerance training, etc.

The world is quite complex and constantly evolving in every way it can be (hopefully in a fasinating direction!). So I use this blog to document some of my thoughts, techniques and new learnings that I feel valuable to share. My hope is that those reflections would be helpful to someone in a good way.
