---
title: "Revisiting Pruning at Initialization Through the Lens of Ramanujan Graph"
collection: conference publications
permalink: /publication/ICLR2023-2023-01-20-Ramanujan-Graph
excerpt: 'Duc N.M Hoang, Shiwei Liu, Radu Marculescu, Zhangyang Wang'
date: 2023-01-20
venue: 'The International Conference on Learning Representations, ICLR, Notable-Top-5% Oral.'
paperurl: 'https://openreview.net/forum?id=uVcDssQff_'
---

Pruning neural networks at initialization (PaI) has received an upsurge of interest due to its end-to-end saving potential. PaI is able to find sparse subnetworks at initialization that can achieve comparable performance to the full networks on different scores. These methods can surpass the trivial baseline of random pruning but suffer from a significant performance gap compared to post-training pruning. Previous approaches firmly rely on weights, gradients, and sanity checks as primary signals when conducting PaI analysis. To better understand the underlying mechanism of PaI, we propose to interpret it through the lens of the Ramanujan Graph - a class of expander graphs that are sparse while being highly connected. It is believed there should be a strong correlation between the Ramanujan graph and PaI since both are about finding sparse and well-connected neural networks. However, the finer-grained link relating highly sparse and connected networks to their relative performance (i.e., ranking of difference sparse structures at the same specific global sparsity) is still missing. We observe that not only the Ramanujan property for sparse networks shows no significant relationship to PaI’s relative performance, but maximizing it can also lead to the formation of pseudo-random graphs with no structural meanings. We reveal the underlying cause to be Ramanujan Graph’s highly draconian assumption on the upper bound of the third largest eigenvalues (ˆμ)  of layers belonging to highly sparse networks. We hence propose Iterative Mean Difference of Bound (IMDB) as a mean to relax the ˆμ upper bound. Likewise, we also show there exists a lower bound for ˆμ, which we call the NormAlized Random Coefficient (NaRC), that give us an accurate assessment for when sparse but highly connected structure degenerates into naive randomness. Finally, we systematically analyze the behavior of various PaI methods and demonstrate the utility of our proposed metrics in characterizing PaI performance. We show subnetworks preserving better IMDB property correlate higher in performance, while NaRC provides us with a possible mean to locate the region where highly connected, highly sparse, and non-trivial Ramanujan expanders exist. Codes will be made available upon acceptance. 

[Download paper here](https://openreview.net/forum?id=uVcDssQff_)


## Citation
If you find this paper interesting, please cite this paper.
```
@inproceedings{
hoang2023revisiting,
title={{REVISITING} {PRUNING} {AT} {INITIALIZATION} {THROUGH} {THE} {LENS} {OF} {RAMANUJAN} {GRAPH}},
author={Duc N.M Hoang and Shiwei Liu and Radu Marculescu and Zhangyang Wang},
booktitle={International Conference on Learning Representations},
year={2023},
url={https://openreview.net/forum?id=uVcDssQff_}
}
```
