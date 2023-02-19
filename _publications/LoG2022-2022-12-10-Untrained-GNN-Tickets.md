---
title: "You Can Have Better Graph Neural Networks by Not Training Weights at All: Finding Untrained GNNs Tickets"
collection: conference publications
permalink: /publication/LoG2022-2022-12-10-Untrained-GNN-Tickets
excerpt: 'Tianjin Huang, Tianlong Chen, Meng Fang, Vlado Menkovski, Jiaxu Zhao, Lu Yin, Yulong Pei, Decebal Constantin Mocanu, Zhangyang Wang, Mykola Pechenizkiy, **Shiwei Liu**'
date: 2022-12-10
venue: 'Proceedings of the First Learning on Graphs Conference (LoG 2022), **Best Paper Award**.'
paperurl: 'https://openreview.net/forum?id=dF6aEW3_62O'
---

Recent works have impressively demonstrated that there exists a subnetwork in randomly initialized convolutional neural networks (CNNs) that can match the performance of the fully trained dense networks at initialization, without any optimization of the weights of the network (i.e., untrained networks). However, the presence of such untrained subnetworks in graph neural networks (GNNs) still remains mysterious. In this paper we carry out the first-of-its-kind exploration of discovering matching untrained GNNs. With sparsity as the core tool, we can find \textit{untrained sparse subnetworks} at the initialization, that can match the performance of \textit{fully trained dense} GNNs. Besides this already encouraging finding of comparable performance, we show that the found untrained subnetworks can substantially mitigate the GNN over-smoothing problem, hence becoming a powerful tool to enable deeper GNNs without bells and whistles. We also observe that such sparse untrained subnetworks have appealing performance in out-of-distribution detection and robustness of input perturbations. We evaluate our method across widely-used GNN architectures on various popular datasets including the Open Graph Benchmark (OGB).

[Download paper here](https://openreview.net/forum?id=dF6aEW3_62O)


## Citation
If you find this paper interesting, please cite this paper.
```
@inproceedings{
@article{huang2022you,
  title={You Can Have Better Graph Neural Networks by Not Training Weights at All: Finding Untrained GNNs Tickets},
  author={Huang, Tianjin and Chen, Tianlong and Fang, Meng and Menkovski, Vlado and Zhao, Jiaxu and Yin, Lu and Pei, Yulong and Mocanu, Decebal Constantin and Wang, Zhangyang and Pechenizkiy, Mykola and others},
  journal={arXiv preprint arXiv:2211.15335},
  year={2022}
}
```
