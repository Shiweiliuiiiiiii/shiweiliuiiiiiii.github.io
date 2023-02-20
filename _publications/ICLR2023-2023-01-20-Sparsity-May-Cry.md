---
title: "sparsity May Cry: Let Us Fail (Current) Sparse Neural Networks Together!"
collection: conference publications
permalink: /publication/ICLR2023-2023-01-20-Sparsity-May-Cry
excerpt: '**Shiwei Liu**\*, Tianlong Chen\*, Zhenyu Zhang, Xuxi Chen, Tianjin Huang, AJAY KUMAR JAISWAL, Zhangyang Wang'
date: 2023-01-20
venue: 'The International Conference on Learning Representations, ICLR'
paperurl: 'https://openreview.net/forum?id=J6F3lLg4Kdp'
---

Sparse Neural Networks (SNNs) have received voluminous attention predominantly due to growing computational and memory footprints of consistently exploding parameter count in large-scale models. Similar to their dense counterparts, recent SNNs generalize just as well and are equipped with numerous favorable benefits (e.g., low complexity, high scalability, and robustness), sometimes even better than the original dense networks. As research effort is focused on developing increasingly sophisticated sparse algorithms, it is startling that a comprehensive benchmark to evaluate the effectiveness of these algorithms has been highly overlooked. In absence of a carefully crafted evaluation benchmark, most if not all, sparse algorithms are evaluated against fairly simple and naive tasks (eg. CIFAR-10/100, ImageNet, GLUE, etc.), which can potentially camouflage many advantages as well unexpected predicaments of SNNs. In pursuit of a more general evaluation and unveiling the true potential of sparse algorithms, we introduce "Sparsity May Cry" Benchmark (SMC-Bench), a collection of carefully curated 4 diverse tasks with 12 datasets, that accounts for capturing a wide-range of domain-specific knowledge. Our systemic evaluation of representative SOTA sparse algorithms reveals an important obscured observation: all of the SOTA sparse algorithms bluntly fail to perform on SMC-Bench, sometimes at significantly trivial sparsity as low as 5%, which sought immediate attention of sparsity community to reconsider the highly proclaimed benefits of SNNs. By incorporating these well-thought and diverse tasks, SMC-Bench is designed to favor and encourage the development of highly generalizable sparse algorithms.
We plan to open-source SMC-Bench evaluation suite to encourage sparsity researchers and assist them in building next-generation sparse algorithms with the potential to generalize on complex and practical tasks.

[Download paper here](https://openreview.net/forum?id=J6F3lLg4Kdp)


## Citation
If you find this paper interesting, please cite this paper.
```
@inproceedings{liu2023sparsity,
  title={Sparsity May Cry: Let Us Fail (Current) Sparse Neural Networks Together!},
  author={Liu, Shiwei and Chen, Tianlong and Zhang, Zhenyu and Chen, Xuxi and Huang, Tianjin and JAISWAL, AJAY KUMAR and Wang, Zhangyang},
  booktitle={International Conference on Learning Representations},
  year={2023}
}
```
