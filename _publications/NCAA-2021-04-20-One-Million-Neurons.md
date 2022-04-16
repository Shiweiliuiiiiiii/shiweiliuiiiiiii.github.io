---
title: "Sparse evolutionary Deep Learning with over one million artificial neurons on commodity hardware"
collection: journal publications
permalink: /publication/ICLR2022-2022-01-20-Random-Pruning
excerpt: '**Shiwei Liu**, Decebal Constantin Mocanu, Amarsagar Reddy Ramapuram Matavalam, Yulong Pei, Mykola Pechenizkiy'
date: 2021-04-20
venue: 'Neural Computing and Applications'
paperurl: 'https://link.springer.com/article/10.1007/s00521-020-05136-7'
---

Artificial neural networks (ANNs) have emerged as hot topics in the research community. Despite the success of ANNs, it is challenging to train and deploy modern ANNs on commodity hardware due to the ever-increasing model size and the unprecedented growth in the data volumes. Particularly for microarray data, the very high dimensionality and the small number of samples make it difficult for machine learning techniques to handle. Furthermore, specialized hardware such as graphics processing unit (GPU) is expensive. Sparse neural networks are the leading approaches to address these challenges. However, off-the-shelf sparsity-inducing techniques either operate from a pretrained model or enforce the sparse structure via binary masks. The training efficiency of sparse neural networks cannot be obtained practically. In this paper, we introduce a technique allowing us to train truly sparse neural networks with fixed parameter count throughout training. Our experimental results demonstrate that our method can be applied directly to handle high-dimensional data, while achieving higher accuracy than the traditional two-phase approaches. Moreover, we have been able to create truly sparse multilayer perceptron models with over one million neurons and to train them on a typical laptop without GPU (https://github.com/dcmocanu/sparse-evolutionary-artificial-neural-networks/tree/master/SET-MLP-Sparse-Python-Data-Structures), this being way beyond what is possible with any state-of-the-art technique.
[Download paper here](https://openreview.net/forum?id=VBZJ_3tz-t)


## Citation
If you find this paper interesting, please cite this paper.
```
@article{liu2021sparse,
  title={Sparse evolutionary deep learning with over one million artificial neurons on commodity hardware},
  author={Liu, Shiwei and Mocanu, Decebal Constantin and Matavalam, Amarsagar Reddy Ramapuram and Pei, Yulong and Pechenizkiy, Mykola},
  journal={Neural Computing and Applications},
  volume={33},
  number={7},
  pages={2589--2604},
  year={2021},
  publisher={Springer}
}
```
