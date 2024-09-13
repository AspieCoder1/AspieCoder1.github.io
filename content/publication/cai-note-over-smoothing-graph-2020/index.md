---
title: A Note on Over-Smoothing for Graph Neural Networks
authors:
- Chen Cai
- Yusu Wang
date: '2020-06-23'
publishDate: '2024-09-13T09:52:57.899041Z'
publication_types:
- manuscript
abstract: Graph Neural Networks (GNNs) have achieved a lot of success on graph-structured
  data. However, it is observed that the performance of graph neural networks does
  not improve as the number of layers increases. This effect, known as over-smoothing,
  has been analyzed mostly in linear cases. In this paper, we build upon previous
  results  citeoono2019graph to further analyze the over-smoothing effect in the general
  graph neural network architecture. We show when the weight matrix satisfies the
  conditions determined by the spectrum of augmented normalized Laplacian, the Dirichlet
  energy of embeddings will converge to zero, resulting in the loss of discriminative
  power. Using Dirichlet energy to measure \"expressiveness\" of embedding is conceptually
  clean; it leads to simpler proofs than  citeoono2019graph and can handle more non-linearities.
tags:
- Computer Science - Machine Learning
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2006.13318
---
