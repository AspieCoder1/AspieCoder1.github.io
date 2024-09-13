---
title: Efficient Sharpness-aware Minimization for Improved Training of Neural Networks
authors:
- Jiawei Du
- Hanshu Yan
- Jiashi Feng
- Joey Tianyi Zhou
- Liangli Zhen
- Rick Siow Mong Goh
- Vincent Tan
date: '2021-10-06'
publishDate: '2024-09-13T09:52:58.123558Z'
publication_types:
- paper-conference
abstract: Overparametrized Deep Neural Networks (DNNs) often achieve astounding performances,
  but may potentially result in severe generalization error. Recently, the relation
  between the sharpness of the loss landscape and the generalization error has been
  established by Foret et al. (2020), in which the Sharpness Aware Minimizer (SAM)
  was proposed to mitigate the degradation of the generalization. Unfortunately, SAM’s
  computational cost is roughly double that of base optimizers, such as Stochastic
  Gradient Descent (SGD). This paper thus proposes Efficient Sharpness Aware Minimizer
  (ESAM), which boosts SAM’s efficiency at no cost to its generalization performance.
  ESAM includes two novel and efficient training strategies—StochasticWeight Perturbation
  and Sharpness-Sensitive Data Selection. In the former, the sharpness measure is
  approximated by perturbing a stochastically chosen set of weights in each iteration;
  in the latter, the SAM loss is optimized using only a judiciously selected subset
  of data that is sensitive to the sharpness. We provide theoretical explanations
  as to why these strategies perform well. We also show, via extensive experiments
  on the CIFAR and ImageNet datasets, that ESAM enhances the efficiency over SAM from
  requiring 100% extra computations to 40% vis-`a-vis base optimizers, while test
  accuracies are preserved or even improved.
links:
- name: URL
  url: https://openreview.net/forum?id=n0OeTdNRG0Q
---
