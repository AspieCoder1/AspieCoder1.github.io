---
title: Efficient Orthogonal Parametrisation of Recurrent Neural Networks Using Householder
  Reflections
authors:
- Zakaria Mhammedi
- Andrew Hellicar
- Ashfaqur Rahman
- James Bailey
date: '2017-07-17'
publishDate: '2024-09-13T09:52:58.920211Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 34th International Conference on Machine Learning*'
abstract: The problem of learning long-term dependencies in sequences using Recurrent
  Neural Networks (RNNs) is still a major challenge. Recent methods have been suggested
  to solve this problem by constraining the transition matrix to be unitary during
  training which ensures that its norm is equal to one and prevents exploding gradients.
  These methods either have limited expressiveness or scale poorly with the size of
  the network when compared with the simple RNN case, especially when using stochastic
  gradient descent with a small mini-batch size. Our contributions are as follows;
  we first show that constraining the transition matrix to be unitary is a special
  case of an orthogonal constraint. Then we present a new parametrisation of the transition
  matrix which allows efficient training of an RNN while ensuring that the matrix
  is always orthogonal. Our results show that the orthogonal constraint on the transition
  matrix applied through our parametrisation gives similar benefits to the unitary
  constraint, without the time complexity limitations.
links:
- name: URL
  url: https://proceedings.mlr.press/v70/mhammedi17a.html
---