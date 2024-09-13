---
title: GPU accelerated t-distributed stochastic neighbor embedding
authors:
- David M. Chan
- Roshan Rao
- Forrest Huang
- John F. Canny
date: '2019-09-01'
publishDate: '2024-09-13T09:52:57.934759Z'
publication_types:
- article-journal
abstract: Modern datasets and models are notoriously difficult to explore and analyze
  due to their inherent high dimensionality and massive numbers of samples. Existing
  visualization methods which employ dimensionality reduction to two or three dimensions
  are often inefficient and/or ineffective for these datasets. This paper introduces
  t-SNE-CUDA, a GPU-accelerated implementation of t-Distributed Symmetric Neighbor
  Embedding (t-SNE) for visualizing datasets and models. t-SNE-CUDA significantly
  outperforms current implementations with 15-700x speedups on the CIFAR-10 and MNIST
  datasets. These speedups enable, for the first time, large scale visualizations
  of modern computer vision datasets such as ImageNet, as well as larger NLP datasets
  such as GloVe. From these new visualizations, we can draw a number of interesting
  conclusions. In addition, the performance on machine learning datasets allows us
  to compute t-SNE embeddings in close to real time, and we explore the applications
  of such fast embeddings in the domain of importance sampling for neural network
  training.
tags:
- Applications
- CUDA
- Embedding
- GPU computing
- Parallel computing
- T-SNE
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S074373151830875X
---
