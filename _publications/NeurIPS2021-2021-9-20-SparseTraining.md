---
title: "Sparse Training via Boosting Pruning Plasticity with Neuroregeneration"
collection: conference publications
permalink: /publication/NeurIPS2021-2021-9-20-SparseTraining
excerpt: '**Shiwei Liu**, Tianlong Chen, Xiaohan Chen, Zahra Atashgahi, Lu Yin, Huanyu Kou, Li Shen, Mykola Pechenizkiy, Zhangyang Wang, Decebal Constantin Mocanu'
date: 2021-09-20
venue: 'The International Conference on Learning Representations, ICLR'
paperurl: 'https://arxiv.org/pdf/2106.10404.pdf'
---

Works on lottery ticket hypothesis (LTH) and single-shot network pruning (SNIP) have raised a lot of attention currently on post-training pruning (iterative magnitude pruning), and before-training pruning (pruning at initialization). The former method suffers from an extremely large computation cost and the latter usually struggles with insufficient performance. In comparison, during-training pruning, a class of pruning methods that simultaneously enjoys the training/inference efficiency and the comparable performance, temporarily, has been less explored. To better understand during-training pruning, we quantitatively study the effect of pruning throughout training from the perspective of pruning plasticity (the ability of the pruned networks to recover the original performance). Pruning plasticity can help explain several other empirical observations about neural network pruning in literature. We further find that pruning plasticity can be substantially improved by injecting a brain-inspired mechanism called neuroregeneration, i.e., to regenerate the same number of connections as pruned. We design a novel gradual magnitude pruning (GMP) method, named gradual pruning with zero-cost neuroregeneration (GraNet), that advances state of the art. Perhaps most impressively, its sparse-to-sparse version for the first time boosts the sparse-to-sparse training performance over various dense-to-sparse methods with ResNet-50 on ImageNet without extending the training time. We release all codes in https://github.com/Shiweiliuiiiiiii/GraNet.


[Paper](https://openreview.net/forum?id=MNVjrDpu6Yo) [Code](https://github.com/VITA-Group/GraNet)


## Citation
If you find this paper interesting, please cite this paper.
```
@article{liu2021sparse,
  title={Sparse training via boosting pruning plasticity with neuroregeneration},
  author={Liu, Shiwei and Chen, Tianlong and Chen, Xiaohan and Atashgahi, Zahra and Yin, Lu and Kou, Huanyu and Shen, Li and Pechenizkiy, Mykola and Wang, Zhangyang and Mocanu, Decebal Constantin},
  journal={Advances in Neural Information Processing Systems},
  volume={34},
  year={2021}
}
```
