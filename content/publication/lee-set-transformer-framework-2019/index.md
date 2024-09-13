---
title: 'Set Transformer: A Framework for Attention-based Permutation-Invariant Neural
  Networks'
authors:
- Juho Lee
- Yoonho Lee
- Jungtaek Kim
- Adam Kosiorek
- Seungjin Choi
- Yee Whye Teh
date: '2019-05-24'
publishDate: '2024-09-13T09:52:58.757177Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 36th International Conference on Machine Learning*'
abstract: Many machine learning tasks such as multiple instance learning, 3D shape
  recognition, and few-shot image classification are defined on sets of instances.
  Since solutions to such problems do not depend on the order of elements of the set,
  models used to address them should be permutation invariant. We present an attention-based
  neural network module, the Set Transformer, specifically designed to model interactions
  among elements in the input set. The model consists of an encoder and a decoder,
  both of which rely on attention mechanisms. In an effort to reduce computational
  complexity, we introduce an attention scheme inspired by inducing point methods
  from sparse Gaussian process literature. It reduces the computation time of self-attention
  from quadratic to linear in the number of elements in the set. We show that our
  model is theoretically attractive and we evaluate it on a range of tasks, demonstrating
  the state-of-the-art performance compared to recent methods for set-structured data.
links:
- name: URL
  url: https://proceedings.mlr.press/v97/lee19d.html
---