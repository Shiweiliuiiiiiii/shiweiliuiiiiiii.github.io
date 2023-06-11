---
title: "Are Large Kernels Better Teachers than Transformers for ConvNets?"
collection: conference publications
permalink: /publication/ICML2023-2023-04-24-L2S-Kernel-Distillation
excerpt: 'Tianjin Huang, Lu Yin, Zhenyu Zhang, Li Shen, Meng Fang, Mykola Pechenizkiy, Zhangyang Wang, **Shiwei Liu**'
date: 2023-04-24
venue: 'International Conference on Machine Learning, ICML'
paperurl: 'https://arxiv.org/pdf/2305.19412.pdf'
---

This paper reveals a new appeal of the recently emerged large-kernel Convolutional Neural Networks (ConvNets): as the teacher in Knowledge Distillation (KD) for small-kernel ConvNets. 
While Transformers have led state-of-the-art (SOTA) performance in various fields with ever-larger models and labeled data, small-kernel ConvNets are considered more suitable for resource-limited applications due to the efficient convolution operation and compact weight sharing. 
KD is widely used to boost the performance of small-kernel ConvNets. However, previous research shows that it is not quite effective to distill knowledge (e.g., global information) from Transformers to small-kernel ConvNets, presumably due to their disparate architectures. 
We hereby carry out a first-of-its-kind study unveiling that modern large-kernel ConvNets, a compelling competitor to Vision Transformers, are remarkably more effective teachers for small-kernel ConvNets, due to more similar architectures. 
Our findings are backed up by extensive experiments on both logit-level and feature-level KD "out of the box", with no dedicated architectural nor training recipe modifications. 
Notably, we obtain the best-ever pure ConvNet under 30M parameters with 83.1% top-1 accuracy on ImageNet, outperforming current SOTA methods including ConvNeXt V2 and Swin V2. 
We also find that beneficial characteristics of large-kernel ConvNets, e.g., larger effective receptive fields, can be seamlessly transferred to students through this large-to-small kernel distillation. 

[Download paper here](https://arxiv.org/pdf/2305.19412.pdf)


## Citation
If you find this paper interesting, please cite this paper.
```
@article{huang2023large,
  title={Are Large Kernels Better Teachers than Transformers for ConvNets?},
  author={Huang, Tianjin and Yin, Lu and Zhang, Zhenyu and Shen, Li and Fang, Meng and Pechenizkiy, Mykola and Wang, Zhangyang and Liu, Shiwei},
  journal={arXiv preprint arXiv:2305.19412},
  year={2023}
}
```
