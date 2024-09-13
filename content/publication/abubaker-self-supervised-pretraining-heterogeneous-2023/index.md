---
title: Self-Supervised Pretraining for Heterogeneous Hypergraph Neural Networks
authors:
- Abdalgader Abubaker
- Takanori Maehara
- Madhav Nimishakavi
- Vassilis Plachouras
date: '2023-11-19'
publishDate: '2024-09-13T09:52:57.623428Z'
publication_types:
- manuscript
abstract: Recently, pretraining methods for the Graph Neural Networks (GNNs) have
  been successful at learning effective representations from unlabeled graph data.
  However, most of these methods rely on pairwise relations in the graph and do not
  capture the underling higher-order relations between entities. Hypergraphs are versatile
  and expressive structures that can effectively model higher-order relationships
  among entities in the data. Despite the efforts to adapt GNNs to hypergraphs (HyperGNN),
  there are currently no fully self-supervised pretraining methods for HyperGNN on
  heterogeneous hypergraphs. In this paper, we present SPHH, a novel self-supervised
  pretraining framework for heterogeneous HyperGNNs. Our method is able to effectively
  capture higher-order relations among entities in the data in a self-supervised manner.
  SPHH is consist of two self-supervised pretraining tasks that aim to simultaneously
  learn both local and global representations of the entities in the hypergraph by
  using informative representations derived from the hypergraph structure. Overall,
  our work presents a significant advancement in the field of self-supervised pretraining
  of HyperGNNs, and has the potential to improve the performance of various graph-based
  downstream tasks such as node classification and link prediction tasks which are
  mapped to hypergraph configuration. Our experiments on two real-world benchmarks
  using four different HyperGNN models show that our proposed SPHH framework consistently
  outperforms state-of-the-art baselines in various downstream tasks. The results
  demonstrate that SPHH is able to improve the performance of various HyperGNN models
  in various downstream tasks, regardless of their architecture or complexity, which
  highlights the robustness of our framework.
tags:
- Computer Science - Machine Learning
- Computer Science - Social and Information Networks
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2311.11368
---
