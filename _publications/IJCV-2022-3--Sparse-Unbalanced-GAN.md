---
title: "Don’t Be So Dense: Sparse-to-Sparse GAN Training Without Sacrificing Performance"
collection: arxiv preprint
permalink: /publication/IJCV-2022-3--Sparse-Unbalanced-GAN
excerpt: '**Shiwei Liu**, Yuesong Tian, Tianlong Chen, Li Shen'
date: 2023-5-5
venue: 'International Journal of Computer Vision (IJCV)'
paperurl: 'https://arxiv.org/pdf/2203.02770.pdf'
---

Generative adversarial networks (GANs) have received an upsurging interest since being proposed due to the
high quality of the generated data. While achieving increasingly impressive results, the resource demands
associated with the large model size hinders the usage of GANs in resource-limited scenarios. For inference,
the existing model compression techniques can reduce the model complexity with comparable performance.
However, the training efficiency of GANs has less been explored due to the fragile training process of
GANs. In this paper, we, for the first time, explore the possibility of directly training sparse GAN from
scratch without involving any dense or pre-training steps. Even more unconventionally, our proposed method
enables directly training sparse unbalanced GANs with an extremely sparse generator from scratch. Instead
of training full GANs, we start with sparse GANs and dynamically explore the parameter space spanned
over the generator throughout training. Such a sparse-to-sparse training procedure enhances the capacity
of the highly sparse generator progressively while sticking to a fixed small parameter budget with appealing training and inference efficiency gains. Extensive experiments with modern GAN architectures validate
the effectiveness of our method. Our sparsified GANs, trained from scratch in one single run, are able to
outperform the ones learned by expensive iterative pruning and re-training. Perhaps most importantly, we
find instead of inheriting parameters from expensive pre-trained GANs, directly training sparse GANs from
scratch can be a much more efficient solution. For example, only training with a 80% sparse generator
and a 70% sparse discriminator, our method can achieve even better performance than the dense BigGAN.

[Download paper here](https://arxiv.org/pdf/2203.02770.pdf)


## Citation
If you find this paper interesting, please cite this paper.
```
@article{liu2022don,
  title={Don't Be So Dense: Sparse-to-Sparse GAN Training Without Sacrificing Performance},
  author={Liu, Shiwei and Tian, Yuesong and Chen, Tianlong and Shen, Li},
  journal={arXiv preprint arXiv:2203.02770},
  year={2022}
}
```
