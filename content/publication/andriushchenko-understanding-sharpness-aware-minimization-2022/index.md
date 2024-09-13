---
title: Towards Understanding Sharpness-Aware Minimization
authors:
- Maksym Andriushchenko
- Nicolas Flammarion
date: '2022-06-28'
publishDate: '2024-09-13T09:52:57.692167Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 39th International Conference on Machine Learning*'
abstract: Sharpness-Aware Minimization (SAM) is a recent training method that relies
  on worst-case weight perturbations which significantly improves generalization in
  various settings. We argue that the existing justifications for the success of SAM
  which are based on a PAC-Bayes generalization bound and the idea of convergence
  to flat minima are incomplete. Moreover, there are no explanations for the success
  of using m-sharpness in SAM which has been shown as essential for generalization.
  To better understand this aspect of SAM, we theoretically analyze its implicit bias
  for diagonal linear networks. We prove that SAM always chooses a solution that enjoys
  better generalization properties than standard gradient descent for a certain class
  of problems, and this effect is amplified by using m-sharpness. We further study
  the properties of the implicit bias on non-linear networks empirically, where we
  show that fine-tuning a standard model with SAM can lead to significant generalization
  improvements. Finally, we provide convergence results of SAM for non-convex objectives
  when used with stochastic gradients. We illustrate these results empirically for
  deep networks and discuss their relation to the generalization behavior of SAM.
  The code of our experiments is available at https://github.com/tml-epfl/understanding-sam.
links:
- name: URL
  url: https://proceedings.mlr.press/v162/andriushchenko22a.html
---
