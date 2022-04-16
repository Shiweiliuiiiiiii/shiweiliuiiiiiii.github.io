---
title: "Topological Insights into Sparse Neural Networks"
collection: publications
permalink: /publication/ECMLPKDD2021-2020-06-05-Topological Insights into Sparse Neural Networks
excerpt: 'Shiwei Liu, Tim Van der Lee, Anil Yaman, Zahra Atashgahi, Davide Ferraro, Ghada Sokar, Mykola Pechenizkiy, Decebal Constantin Mocanu'
date: 2020-06-05
venue: 'ECMLPKDD'
paperurl: 'https://arxiv.org/pdf/2006.14085.pdf'
---
Sparse neural networks are effective approaches to reduce
the resource requirements for the deployment of deep neural networks.
Recently, the concept of adaptive sparse connectivity, has emerged to
allow training sparse neural networks from scratch by optimizing the
sparse structure during training. However, comparing different sparse
topologies and determining how sparse topologies evolve during training, especially for the situation in which the sparse structure optimization is involved, remain as challenging open questions. This comparison
becomes increasingly complex as the number of possible topological comparisons increases exponentially with the size of networks. In this work,
we introduce an approach to understand and compare sparse neural network topologies from the perspective of graph theory. We first propose
Neural Network Sparse Topology Distance (NNSTD) to measure the
distance between different sparse neural networks. Further, we demonstrate that sparse neural networks can outperform over-parameterized
models in terms of performance, even without any further structure optimization. To the end, we also show that adaptive sparse connectivity
can always unveil a plenitude of sparse sub-networks with very different
topologies which outperform the dense model, by quantifying and comparing their topological evolutionary processes. The latter findings complement the Lottery Ticket Hypothesis by showing that there is a much
more efficient and robust way to find “winning tickets”. Altogether, our
results start enabling a better theoretical understanding of sparse neural
networks, and demonstrate the utility of using graph theory to analyze
them.

[Download paper here](https://arxiv.org/pdf/2006.14085.pdf)

```
@inproceedings{liu2020topological,
  title={Topological insights into sparse neural networks},
  author={Liu, Shiwei and der Lee, Tim Van and Yaman, Anil and Atashgahi, Zahra and Ferraro, Davide and Sokar, Ghada and Pechenizkiy, Mykola and Mocanu, Decebal Constantin},
  booktitle={Joint European conference on machine learning and knowledge discovery in databases},
  pages={279--294},
  year={2020},
  organization={Springer}
}
```
