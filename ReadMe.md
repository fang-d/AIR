<p align="center"><i>An online exemplar-free generalized class-incremental learning approach on imbalanced datasets.</i></p>
<h1 align="center">AIR: Analytic Imbalance Rectifier for Continual Learning</h1>
<h3 align="center">Di Fang, Yinan Zhu, Runze Fang, Cen Chen, Ziqian Zeng, Huiping Zhuang</h3>
<p align="center">
    <a href="https://arxiv.org/abs/2408.10349"><img src="https://img.shields.io/badge/arXiv-2408.10349-b31b1b.svg" alt="arXiv"/></a>
</p>

![AIR-Flowchart](https://github.com/user-attachments/assets/d6634029-ad37-4f1d-b81c-54689537bf43)

## Abstract
Continual learning enables AI models to learn new data sequentially without retraining in real-world scenarios.
Most existing methods assume the training data are balanced, aiming to reduce the catastrophic forgetting problem that models tend to forget previously generated data.
However, data imbalance and the mixture of new and old data in real-world scenarios lead the model to ignore categories with fewer training samples.
To solve this problem, we propose an analytic imbalance rectifier algorithm (AIR), a novel online exemplar-free continual learning method with an analytic (i.e., closed-form) solution for data-imbalanced class-incremental learning (CIL) and generalized CIL scenarios in real-world continual learning.
AIR introduces an analytic re-weighting module (ARM) that calculates a re-weighting factor for each class for the loss function to balance the contribution of each category to the overall loss and solve the problem of imbalanced training data.
AIR uses the least squares technique to give a non-discriminatory optimal classifier and its iterative update method in continual learning.
Experimental results on multiple datasets show that AIR significantly outperforms existing methods in long-tailed and generalized CIL scenarios.

## Implementation
The implementation of the AIR algorithm is **now available at [Analytic-Continual-Learning](https://github.com/ZHUANGHP/Analytic-Continual-Learning)**.
The original implementation will be available in this repository after the paper is accepted.

## Cite this paper
```bib
@misc{AIR_Fang_arXiv2024,
    title         = {{AIR}: Analytic Imbalance Rectifier for Continual Learning}, 
    author        = {Di Fang and Yinan Zhu and Runze Fang and Cen Chen and Ziqian Zeng and Huiping Zhuang},
    year          = {2024},
    month         = {aug},
    archivePrefix = {arXiv},
    primaryClass  = {cs.LG},
    eprint        = {2408.10349},
    doi           = {10.48550/arXiv.2408.10349},
    url           = {https://arxiv.org/abs/2408.10349},
    pdf           = {https://arxiv.org/pdf/2408.10349},
}
```
