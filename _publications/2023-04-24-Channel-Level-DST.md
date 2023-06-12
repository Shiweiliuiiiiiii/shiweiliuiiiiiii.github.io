---
title: "Dynamic Sparsity Is Channel-Level Sparsity Learner"
collection: pre-print
permalink: /publication/2023-04-24-Channel-Level-DST
excerpt: 'Lu Yin, Gen Li, Meng Fang, Li Shen, Tianjin Huang, Zhangyang Wang, Vlado Menkovski, Xiaolong Ma, Mykola Pechenizkiy, **Shiwei Liu**'
date: 2023-04-24
venue: 'Arxiv'
paperurl: 'https://arxiv.org/pdf/2305.19454.pdf'
---

Sparse training has received an upsurging interest in machine learning due to its tantalizing saving potential for the entire training process as well as inference. 
Dynamic sparse training (DST), as a leading sparse training approach, can train deep neural networks at high sparsity from scratch to match the performance of their dense counterparts. 
However, most if not all DST prior arts demonstrate their effectiveness on unstructured sparsity with highly irregular sparse patterns, which receives limited support in common hardware. 
This limitation hinders the usage of DST in practice. In this paper, we propose Channel-aware dynamic sparse (Chase), which for the first time seamlessly translates the promise of unstructured dynamic sparsity to GPU-friendly channel-level sparsity (not fine-grained N:M or group sparsity) during one end-to-end training process, without any ad-hoc operations. The resulting small sparse networks can be directly accelerated by commodity hardware, without using any particularly sparsity-aware hardware accelerators. This appealing outcome is partially motivated by a hidden phenomenon of dynamic sparsity: off-the-shelf unstructured DST implicitly involves biased parameter reallocation across channels, with a large fraction of channels (up to 60\%) being sparser than others. By progressively identifying and removing these channels during training, our approach translates unstructured sparsity to channel-wise sparsity. Our experimental results demonstrate that Chase achieves 1.7 X inference throughput speedup on common GPU devices without compromising accuracy with ResNet-50 on ImageNet. We release our codes in this https URL.

[Download paper here](https://arxiv.org/pdf/2305.19454.pdf)


## Citation
If you find this paper interesting, please cite this paper.
```
@article{yin2023dynamic,
  title={Dynamic Sparsity Is Channel-Level Sparsity Learner},
  author={Yin, Lu and Li, Gen and Fang, Meng and Shen, Li and Huang, Tianjin and Wang, Zhangyang and Menkovski, Vlado and Ma, Xiaolong and Pechenizkiy, Mykola and Liu, Shiwei},
  journal={arXiv preprint arXiv:2305.19454},
  year={2023}
}
```
