---
title: 'LightGCN: Simplifying and Powering Graph Convolution Network for Recommendation'
authors:
- Xiangnan He
- Kuan Deng
- Xiang Wang
- Yan Li
- YongDong Zhang
- Meng Wang
date: '2020-07-25'
publishDate: '2024-09-13T09:52:58.455883Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 43rd International ACM SIGIR Conference on Research
  and Development in Information Retrieval*'
abstract: Graph Convolution Network (GCN) has become new state-of-the-art for collaborative
  filtering. Nevertheless, the reasons of its effectiveness for recommendation are
  not well understood. Existing work that adapts GCN to recommendation lacks thorough
  ablation analyses on GCN, which is originally designed for graph classification
  tasks and equipped with many neural network operations. However, we empirically
  find that the two most common designs in GCNs -- feature transformation and nonlinear
  activation -- contribute little to the performance of collaborative filtering. Even
  worse, including them adds to the difficulty of training and degrades recommendation
  performance. In this work, we aim to simplify the design of GCN to make it more
  concise and appropriate for recommendation. We propose a new model named LightGCN,
  including only the most essential component in GCN -- neighborhood aggregation --
  for collaborative filtering. Specifically, LightGCN learns user and item embeddings
  by linearly propagating them on the user-item interaction graph, and uses the weighted
  sum of the embeddings learned at all layers as the final embedding. Such simple,
  linear, and neat model is much easier to implement and train, exhibiting substantial
  improvements (about 16.0% relative improvement on average) over Neural Graph Collaborative
  Filtering (NGCF) -- a state-of-the-art GCN-based recommender model -- under exactly
  the same experimental setting. Further analyses are provided towards the rationality
  of the simple LightGCN from both analytical and empirical perspectives.
tags:
- collaborative filtering
- embedding propagation
- graph neural network
- recommendation
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3397271.3401063
---
