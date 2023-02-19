---
title: "Lottery Pools: Winning More by Interpolating Tickets without Increasing Training or Inference Cost"
collection: conference publications
permalink: /publication/AAAI2023-2022-11-18-Lottery-Pools.md
excerpt: 'Lu Yin\*, **Shiwei Liu**\*, Meng Fang, Tianjin Huang, Vlado Menkovski, Mykola Pechenizkiy'
date: 2022-11-18
venue: 'AAAI Conference on Artificial Intelligence, AAAI 2023'
paperurl: '[https://openreview.net/forum?id=J6F3lLg4Kdp](https://arxiv.org/abs/2208.10842)'
---

Lottery tickets (LTs) is able to discover accurate and sparse subnetworks that could be trained in isolation to match the performance of dense networks. Ensemble, in parallel, is one of the oldest time-proven tricks in machine learning to improve performance by combining the output of multiple independent models. However, the benefits of ensemble in the context of LTs will be diluted since ensemble does not directly lead to stronger sparse subnetworks, but leverages their predictions for a better decision. In this work, we first observe that directly averaging the weights of the adjacent learned subnetworks significantly boosts the performance of LTs. Encouraged by this observation, we further propose an alternative way to perform an 'ensemble' over the subnetworks identified by iterative magnitude pruning via a simple interpolating strategy. We call our method Lottery Pools. In contrast to the naive ensemble which brings no performance gains to each single subnetwork, Lottery Pools yields much stronger sparse subnetworks than the original LTs without requiring any extra training or inference cost. Across various modern architectures on CIFAR-10/100 and ImageNet, we show that our method achieves significant performance gains in both, in-distribution and out-of-distribution scenarios. Impressively, evaluated with VGG-16 and ResNet-18, the produced sparse subnetworks outperform the original LTs by up to 1.88% on CIFAR-100 and 2.36% on CIFAR-100-C; the resulting dense network surpasses the pre-trained dense-model up to 2.22% on CIFAR-100 and 2.38% on CIFAR-100-C.


[Download paper here](https://arxiv.org/abs/2208.10842)


## Citation
If you find this paper interesting, please cite this paper.
```
@article{yin2022lottery,
  title={Lottery Pools: Winning More by Interpolating Tickets without Increasing Training or Inference Cost},
  author={Yin, Lu and Liu, Shiwei and Meng, Fang and Huang, Tianjin and Menkovski, Vlado and Pechenizkiy, Mykola},
  journal={arXiv preprint arXiv:2208.10842},
  year={2022}
}
```
