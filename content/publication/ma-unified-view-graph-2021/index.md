---
title: A Unified View on Graph Neural Networks as Graph Signal Denoising
authors:
- Yao Ma
- Xiaorui Liu
- Tong Zhao
- Yozen Liu
- Jiliang Tang
- Neil Shah
date: '2021-10-30'
publishDate: '2024-09-13T09:52:58.892839Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 30th ACM International Conference on Information
  & Knowledge Management*'
abstract: Graph Neural Networks (GNNs) have risen to prominence in learning representations
  for graph structured data. A single GNN layer typically consists of a feature transformation
  and a feature aggregation operation. The former normally uses feed-forward networks
  to transform features, while the latter aggregates the transformed features over
  the graph. Numerous recent works have proposed GNN models with different designs
  in the aggregation operation. In this work, we establish mathematically that the
  aggregation processes in a group of representative GNN models including GCN, GAT,
  PPNP, and APPNP can be regarded as (approximately) solving a graph denoising problem
  with a smoothness assumption. Such a unified view across GNNs not only provides
  a new perspective to understand a variety of aggregation operations but also enables
  us to develop a unified graph neural network framework UGNN. To demonstrate its
  promising potential, we instantiate a novel GNN model, ADA-UGNN, derived from UGNN,
  to handle graphs with adaptive smoothness across nodes. Comprehensive experiments
  show the effectiveness of ADA-UGNN.
tags:
- graph neural networks
- graph signal denoising
- semi-supervised classification
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3459637.3482225
---
