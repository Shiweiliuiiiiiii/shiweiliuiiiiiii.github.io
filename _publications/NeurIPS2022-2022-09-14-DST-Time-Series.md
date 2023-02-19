---
title: "Dynamic Sparse Network for Time Series Classification: Learning What to “See”"
collection: conference publications
permalink: /publication/NeurIPS2022-2022-09-14-DST-Time-Series
excerpt: 'Qiao Xiao, Boqian Wu, Yu Zhang, **Shiwei Liu**, Mykola Pechenizkiy, Elena Mocanu, Decebal Constantin Mocanu'
date: 2022-09-14
venue: '36th Annual Conference on Neural Information Processing Systems, NeurIPS2022'
paperurl: 'https://arxiv.org/abs/2212.09840'
---

The receptive field (RF), which determines the region of time series to be seen and used, is critical to improve the performance for time series classification (TSC). However, the variation of signal scales across and within time series data, makes it challenging to decide on proper RF sizes for TSC. In this paper, we propose a dynamic sparse network (DSN) with sparse connections for TSC, which can learn to cover various RF without cumbersome hyper-parameters tuning. The kernels in each sparse layer are sparse and can be explored under the constraint regions by dynamic sparse training, which makes it possible to reduce the resource cost. The experimental results show that the proposed DSN model can achieve state-of-art performance on both univariate and multivariate TSC datasets with less than 50\% computational cost compared with recent baseline methods, opening the path towards more accurate resource-aware methods for time series analyses. Our code is publicly available at: this https URL.
[Download paper here](https://arxiv.org/abs/2212.09840)


## Citation
If you find this paper interesting, please cite this paper.
```
@article{xiao2022dynamic,
  title={Dynamic Sparse Network for Time Series Classification: Learning What to" see''},
  author={Xiao, Qiao and Wu, Boqian and Zhang, Yu and Liu, Shiwei and Pechenizkiy, Mykola and Mocanu, Elena and Mocanu, Decebal Constantin},
  journal={arXiv preprint arXiv:2212.09840},
  year={2022}
}
```
