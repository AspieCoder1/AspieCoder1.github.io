---
title: A Generalization of Transformer Networks to Graphs
authors:
- Vijay Prakash Dwivedi
- Xavier Bresson
date: '2021-01-24'
publishDate: '2024-09-13T09:52:58.152125Z'
publication_types:
- manuscript
abstract: We propose a generalization of transformer neural network architecture for
  arbitrary graphs. The original transformer was designed for Natural Language Processing
  (NLP), which operates on fully connected graphs representing all connections between
  the words in a sequence. Such architecture does not leverage the graph connectivity
  inductive bias, and can perform poorly when the graph topology is important and
  has not been encoded into the node features. We introduce a graph transformer with
  four new properties compared to the standard model. First, the attention mechanism
  is a function of the neighborhood connectivity for each node in the graph. Second,
  the positional encoding is represented by the Laplacian eigenvectors, which naturally
  generalize the sinusoidal positional encodings often used in NLP. Third, the layer
  normalization is replaced by a batch normalization layer, which provides faster
  training and better generalization performance. Finally, the architecture is extended
  to edge feature representation, which can be critical to tasks s.a. chemistry (bond
  type) or link prediction (entity relationship in knowledge graphs). Numerical experiments
  on a graph benchmark demonstrate the performance of the proposed graph transformer
  architecture. This work closes the gap between the original transformer, which was
  designed for the limited case of line graphs, and graph neural networks, that can
  work with arbitrary graphs. As our architecture is simple and generic, we believe
  it can be used as a black box for future applications that wish to consider transformer
  and graphs.
tags:
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2012.09699
---
