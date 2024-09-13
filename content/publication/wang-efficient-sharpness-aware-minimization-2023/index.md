---
title: Efficient Sharpness-Aware Minimization for Molecular Graph Transformer Models
authors:
- Yili Wang
- Kaixiong Zhou
- Ninghao Liu
- Ying Wang
- Xin Wang
date: '2023-10-13'
publishDate: '2024-09-13T09:52:59.470365Z'
publication_types:
- paper-conference
abstract: 'Sharpness-aware minimization (SAM) has received increasing attention in
  computer vision since it can effectively eliminate the sharp local minima from the
  training trajectory and mitigate generalization degradation. However, SAM requires
  two sequential gradient computations during the optimization of each step: one to
  obtain the perturbation gradient and the other to obtain the updating gradient.
  Compared with the base optimizer (e.g., Adam), SAM doubles the time overhead due
  to the additional perturbation gradient. By dissecting the theory of SAM and observing
  the training gradient of the molecular graph transformer, we propose a new algorithm
  named GraphSAM, which reduces the training cost of SAM and improves the generalization
  performance of graph transformer models. There are two key factors that contribute
  to this result: (i)  textitgradient approximation: we use the updating gradient
  of the previous step to approximate the perturbation gradient at the intermediate
  steps smoothly ( textbfincreases efficiency); (ii)  textitloss landscape approximation:
  we theoretically prove that the loss landscape of GraphSAM is limited to a small
  range centered on the expected loss of SAM ( textbfguarantees generalization performance).
  The extensive experiments on six datasets with different tasks demonstrate the superiority
  of GraphSAM, especially in optimizing the model update process.'
links:
- name: URL
  url: https://openreview.net/forum?id=Od39h4XQ3Y
---
