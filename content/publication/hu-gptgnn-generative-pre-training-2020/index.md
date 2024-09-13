---
title: 'GPT-GNN: Generative Pre-Training of Graph Neural Networks'
authors:
- Ziniu Hu
- Yuxiao Dong
- Kuansan Wang
- Kai-Wei Chang
- Yizhou Sun
date: '2020-08-20'
publishDate: '2024-09-13T09:52:58.559145Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 26th ACM SIGKDD International Conference on Knowledge
  Discovery & Data Mining*'
abstract: 'Graph neural networks (GNNs) have been demonstrated to be powerful in modeling
  graph-structured data. However, training GNNs requires abundant task-specific labeled
  data, which is often arduously expensive to obtain. One effective way to reduce
  the labeling effort is to pre-train an expressive GNN model on unlabelled data with
  self-supervision and then transfer the learned model to downstream tasks with only
  a few labels. In this paper, we present the GPT-GNN framework to initialize GNNs
  by generative pre-training. GPT-GNN introduces a self-supervised attributed graph
  generation task to pre-train a GNN so that it can capture the structural and semantic
  properties of the graph. We factorize the likelihood of graph generation into two
  components: 1) attribute generation and 2) edge generation. By modeling both components,
  GPT-GNN captures the inherent dependency between node attributes and graph structure
  during the generative process. Comprehensive experiments on the billion-scale open
  academic graph and Amazon recommendation data demonstrate that GPT-GNN significantly
  outperforms state-of-the-art GNN models without pre-training by up to 9.1% across
  various downstream tasks?'
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3394486.3403237
---
