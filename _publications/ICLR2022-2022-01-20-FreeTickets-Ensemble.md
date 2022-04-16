---
title: "Deep Ensembling with No Overhead for either Training or Testing: The All-Round Blessings of Dynamic Sparsity"
collection: publications
permalink: /publication/ICLR2022-2022-01-20-FreeTickets-Ensemble
excerpt: 'Shiwei Liu, Tianlong Chen, Zahra Atashgahi, Xiaohan Chen, Ghada Sokar, Elena Mocanu, Mykola Pechenizkiy, Zhangyang Wang, Decebal Constantin Mocanu'
date: 2022-01-20
venue: 'The International Conference on Learning Representations, ICLR'
paperurl: 'https://openreview.net/forum?id=RLtqs6pzj1-'
---
The success of deep ensembles on improving predictive performance, uncertainty estimation, and out-of-distribution robustness has been extensively studied in the machine learning literature. Albeit the promising results, naively training multiple deep neural networks and combining their predictions at inference leads to prohibitive computational costs and memory requirements. Recently proposed efficient ensemble approaches reach the performance of the traditional deep ensembles with significantly lower costs. However, the training resources required by these approaches are still at least the same as training a single dense model. In this work, we draw a unique connection between sparse neural network training and deep ensembles, yielding a novel efficient ensemble learning framework called . Instead of training multiple dense networks and averaging them, we directly train sparse subnetworks from scratch and extract diverse yet accurate subnetworks during this efficient, sparse-to-sparse training. Our framework, , is defined as the ensemble of these relatively cheap sparse subnetworks. Despite being an ensemble method,  has even fewer parameters and training FLOPs than a single dense model. This seemingly counter-intuitive outcome is due to the ultra training/inference efficiency of dynamic sparse training.  surpasses the dense baseline in all the following criteria: prediction accuracy, uncertainty estimation, out-of-distribution (OoD) robustness, as well as efficiency for both training and inference. Impressively,  outperforms the naive deep ensemble with ResNet50 on ImageNet using around only  of the training FLOPs required by the latter. We have released our source code at https://github.com/VITA-Group/FreeTickets.

[Download paper here](https://openreview.net/forum?id=RLtqs6pzj1-)

```
@inproceedings{
liu2022deep,
title={Deep Ensembling with No Overhead for either Training or Testing: The All-Round Blessings of Dynamic Sparsity},
author={Shiwei Liu and Tianlong Chen and Zahra Atashgahi and Xiaohan Chen and Ghada Sokar and Elena Mocanu and Mykola Pechenizkiy and Zhangyang Wang and Decebal Constantin Mocanu},
booktitle={International Conference on Learning Representations},
year={2022},
url={https://openreview.net/forum?id=RLtqs6pzj1-}
}
```
