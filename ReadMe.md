<p align="center"><i>An online exemplar-free generalized class-incremental learning approach on imbalanced datasets.</i></p>
<h1 align="center">AIR: Analytic Imbalance Rectifier for Continual Learning</h1>
<h3 align="center">Di Fang, Yinan Zhu, Zhiping Lin, Cen Chen, Ziqian Zeng, Huiping Zhuang</h3>
<p align="center">
    <a href="https://arxiv.org/abs/2408.10349"><img src="https://img.shields.io/badge/arXiv-2408.10349-b31b1b.svg" alt="arXiv"/></a>
</p>

![AIR-Flowchart](https://github.com/user-attachments/assets/89bf9fad-5c91-40c1-b7e1-8ab9e5deb9f2)

## Abstract
Continual learning agents incrementally learn from sequentially arriving data and adapt to the dynamic, ever-changing nature of real-world environments. However, many existing continual learning methods assume the incoming data is balanced and thus face performance degradation under real-world environments where class distributions are often imbalanced and shift over time. We reveal that the leading cause of this performance degradation is the skewed loss function, where classes with fewer training samples are given less attention. To deal with this challenge, we propose an analytic imbalance rectifier (AIR) algorithm. AIR is an online exemplar-free approach with a closed-form incremental classifier whose weight equals joint learning weight. In particular, AIR addresses class imbalance with an analytic re-weighting module (ARM) that calculates a re-weighting factor for each class in the loss function to balance each class's contribution to the overall loss. Experiments on multiple datasets show that AIR significantly outperforms existing methods in long-tailed and generalized continual learning.

## Implementation
The implementation of the AIR algorithm is **now available at [Analytic-Continual-Learning](https://github.com/ZHUANGHP/Analytic-Continual-Learning)**.
The original implementation will be available in this repository after the paper is accepted.

## Cite this paper
```bib
@misc{AIR_Fang_arXiv2024,
    title         = {{AIR}: Analytic Imbalance Rectifier for Continual Learning}, 
    author        = {Di Fang and Yinan Zhu and Zhiping Lin and Cen Chen and Ziqian Zeng and Huiping Zhuang},
    year          = {2024},
    archivePrefix = {arXiv},
    primaryClass  = {cs.LG},
    eprint        = {2408.10349},
    doi           = {10.48550/arXiv.2408.10349},
    url           = {https://arxiv.org/abs/2408.10349},
    pdf           = {https://arxiv.org/pdf/2408.10349},
}
```
