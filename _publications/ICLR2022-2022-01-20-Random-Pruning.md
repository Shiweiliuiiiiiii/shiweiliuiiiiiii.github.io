---
title: "The Unreasonable Effectiveness of Random Pruning: Return of the Most Naive Baseline for Sparse Training"
collection: conference publications
permalink: /publication/ICLR2022-2022-01-20-Random-Pruning
excerpt: '**Shiwei Liu**, Tianlong Chen, Xiaohan Chen, Li Shen, Decebal Constantin Mocanu, Zhangyang Wang, Mykola Pechenizkiy'
date: 2022-01-20
venue: 'The International Conference on Learning Representations, ICLR'
paperurl: 'https://openreview.net/forum?id=VBZJ_3tz-t'
---

Random pruning is arguably the most naive way to attain sparsity in neural networks, but has been deemed uncompetitive by either post-training pruning or sparse training. In this paper, we focus on sparse training and highlight a perhaps counter-intuitive finding, that random pruning at initialization can be quite powerful for the sparse training of modern neural networks. Without any delicate pruning criteria or carefully pursued sparsity structures, we empirically demonstrate that sparsely training a randomly pruned network from scratch can match the performance of its dense equivalent. There are two key factors that contribute to this revival: (i) : as the original dense networks grow wider and deeper, the performance of training a randomly pruned sparse network will quickly grow to matching that of its dense equivalent, even at high sparsity ratios; (ii)  can be pre-chosen for sparse training, which shows to be another important performance booster. Simple as it looks,  a randomly pruned subnetwork of Wide ResNet-50 can be sparsely trained to outperforming a dense Wide ResNet-50, on ImageNet. We also observed such randomly pruned networks outperform dense counterparts in other favorable aspects, such as out-of-distribution detection, uncertainty estimation, and adversarial robustness. Overall, our results strongly suggest there is larger-than-expected room for sparse training at scale, and the benefits of sparsity might be more universal beyond carefully designed pruning. Our source code can be found at https://github.com/VITA-Group/Random_Pruning.


[Download paper here](https://openreview.net/forum?id=VBZJ_3tz-t)


## Citation
If you find this paper interesting, please cite this paper.
```
@inproceedings{
liu2022the,
title={The Unreasonable Effectiveness of Random Pruning: Return of the Most Naive Baseline for Sparse Training},
author={Shiwei Liu and Tianlong Chen and Xiaohan Chen and Li Shen and Decebal Constantin Mocanu and Zhangyang Wang and Mykola Pechenizkiy},
booktitle={International Conference on Learning Representations},
year={2022},
url={https://openreview.net/forum?id=VBZJ_3tz-t}
}
```
