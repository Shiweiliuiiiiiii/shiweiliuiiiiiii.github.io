---
title: "Superposing Many Tickets into One: A Performance Booster for Sparse Neural Network Training"
collection: conference publications
permalink: /publication/UAI2022-2022-06-01-Superposing-Tickets.md
excerpt: 'Lu Yin, Vlado Menkovski, Meng Fang, Tianjin Huang, Yulong Pei, Mykola Pechenizkiy, Decebal Constantin Mocanu, **Shiwei Liu**'
date: 2022-06-01
venue: 'Conference on Uncertainty in Artificial Intelligence (UAI 2022).'
paperurl: 'https://arxiv.org/pdf/2205.15322.pdf'
---

Recent works on sparse neural network training (sparse training) have shown that a compelling trade-off between performance and efficiency can be achieved by training intrinsically sparse neural networks from scratch. Existing sparse training methods usually strive to find the best sparse subnetwork possible in one single run, without involving any expensive dense or pre-training steps. For instance, dynamic sparse training (DST), is capable of reaching a competitive performance of dense training by iteratively evolving the sparse topology during the course of training. In this paper, we argue that it is better to allocate the limited resources to create multiple low-loss sparse subnetworks and superpose them into a stronger one, instead of allocating all resources entirely to find an individual subnetwork. To achieve this, two desiderata are required: (1) efficiently producing many low-loss subnetworks, the so-called cheap tickets, within one training process limited to the standard training time used in dense training; (2) effectively superposing these cheap tickets into one stronger subnetwork. To corroborate our conjecture, we present a novel sparse training approach, termed Sup-tickets, which can satisfy the above two desiderata concurrently in a single sparse-to-sparse training process. Across various modern architectures on CIFAR-10/100 and ImageNet, we show that Sup-tickets integrates seamlessly with the existing sparse training methods and demonstrates consistent performance improvement.


[Download paper here](https://arxiv.org/pdf/2205.15322.pdf)


## Citation
If you find this paper interesting, please cite this paper.
```
@inproceedings{yin2022superposing,
  title={Superposing many tickets into one: A performance booster for sparse neural network training},
  author={Yin, Lu and Menkovski, Vlado and Fang, Meng and Huang, Tianjin and Pei, Yulong and Pechenizkiy, Mykola},
  booktitle={Uncertainty in Artificial Intelligence},
  pages={2267--2277},
  year={2022},
  organization={PMLR}
}
```
