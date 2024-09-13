---
title: Cooperative Graph Neural Networks
authors:
- Ben Finkelshtein
- Xingyue Huang
- Michael Bronstein
- İsmail İlkan Ceylan
date: '2023-10-02'
publishDate: '2024-09-13T09:52:58.192291Z'
publication_types:
- manuscript
abstract: "Graph neural networks are popular architectures for graph machine learning,
  based on iterative computation of node representations of an input graph through
  a series of invariant transformations. A large class of graph neural networks follow
  a standard message-passing paradigm: at every layer, each node state is updated
  based on an aggregate of messages from its neighborhood. In this work, we propose
  a novel framework for training graph neural networks, where every node is viewed
  as a player that can choose to either 'listen', 'broadcast', 'listen and broadcast',
  or to 'isolate'. The standard message propagation scheme can then be viewed as a
  special case of this framework where every node 'listens and broadcasts' to all
  neighbors. Our approach offers a more flexible and dynamic message-passing paradigm,
  where each node can determine its own strategy based on their state, effectively
  exploring the graph topology while learning. We provide a theoretical analysis of
  the new message-passing scheme which is further supported by an extensive empirical
  analysis on a synthetic dataset and on real-world datasets."
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2310.01267
---
