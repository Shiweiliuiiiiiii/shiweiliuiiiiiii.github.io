---
title: "Selfish sparse rnn training"
collection: publications
permalink: /publication/ICML2021-2021-05-20-In-Time-Over-Parameterization
excerpt: '**Shiwei Liu**, Decebal Constantin Mocanu, Yulong Pei, Mykola Pechenizkiy'
date: 2021-05-20
venue: 'Proceedings of Machine Learning Research, ICML'
paperurl: 'http://proceedings.mlr.press/v139/liu21p.html'
---
Sparse neural networks have been widely applied to reduce the computational demands of training and deploying over-parameterized deep neural networks. For inference acceleration, methods that discover a sparse network from a pre-trained dense network (dense-to-sparse training) work effectively. Recently, dynamic sparse training (DST) has been proposed to train sparse neural networks without pre-training a dense model (sparse-to-sparse training), so that the training process can also be accelerated. However, previous sparse-to-sparse methods mainly focus on Multilayer Perceptron Networks (MLPs) and Convolutional Neural Networks (CNNs), failing to match the performance of dense-to-sparse methods in the Recurrent Neural Networks (RNNs) setting. In this paper, we propose an approach to train intrinsically sparse RNNs with a fixed parameter count in one single run, without compromising performance. During training, we allow RNN layers to have a non-uniform redistribution across cell gates for better regularization. Further, we propose SNT-ASGD, a novel variant of the averaged stochastic gradient optimizer, which significantly improves the performance of all sparse training methods for RNNs. Using these strategies, we achieve state-of-the-art sparse training results, better than the dense-to-sparse methods, with various types of RNNs on Penn TreeBank and Wikitext-2 datasets. Our codes are available at https://github.com/Shiweiliuiiiiiii/Selfish-RNN.

[Download paper here](http://proceedings.mlr.press/v139/liu21p.html)

```
@inproceedings{liu2021selfish,
  title={Selfish sparse rnn training},
  author={Liu, Shiwei and Mocanu, Decebal Constantin and Pei, Yulong and Pechenizkiy, Mykola},
  booktitle={International Conference on Machine Learning},
  pages={6893--6904},
  year={2021},
  organization={PMLR}
}
```
