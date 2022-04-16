---
title: "Do We Actually Need Dense Over-Parameterization? In-Time Over-Parameterization in Sparse Training"
collection: publications
permalink: /publication/ICML2021-2021-05-20-In-Time-Over-Parameterization
excerpt: 'Shiwei Liu, Lu Yin, Decebal Constantin Mocanu, Mykola Pechenizkiy'
date: 2021-05-20
venue: 'Proceedings of Machine Learning Research, ICML'
paperurl: 'http://proceedings.mlr.press/v139/liu21y/liu21y.pdf'
---
In this paper, we introduce a new perspective on training deep neural networks capable of state-of-the-art performance without the need for the expensive over-parameterization by proposing the concept of In-Time Over-Parameterization (ITOP) in sparse training. By starting from a random sparse network and continuously exploring sparse connectivities during training, we can perform an Over-Parameterization over the course of training, closing the gap in the expressibility between sparse training and dense training. We further use ITOP to understand the underlying mechanism of Dynamic Sparse Training (DST) and discover that the benefits of DST come from its ability to consider across time all possible parameters when searching for the optimal sparse connectivity. As long as sufficient parameters have been reliably explored, DST can outperform the dense neural network by a large margin. We present a series of experiments to support our conjecture and achieve the state-of-the-art sparse training performance with ResNet-50 on ImageNet. More impressively, ITOP achieves dominant performance over the overparameterization-based sparse methods at extreme sparsities. When trained with ResNet-34 on CIFAR-100, ITOP can match the performance of the dense model at an extreme sparsity 98%.

[Download paper here](http://proceedings.mlr.press/v139/liu21y.html)

```
@inproceedings{liu2021we,
  title={Do we actually need dense over-parameterization? in-time over-parameterization in sparse training},
  author={Liu, Shiwei and Yin, Lu and Mocanu, Decebal Constantin and Pechenizkiy, Mykola},
  booktitle={International Conference on Machine Learning},
  pages={6989--7000},
  year={2021},
  organization={PMLR}
}
```
