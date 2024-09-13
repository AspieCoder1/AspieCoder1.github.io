---
title: Datasets, tasks, and training methods for large-scale hypergraph learning
authors:
- Sunwoo Kim
- Dongjin Lee
- Yul Kim
- Jungho Park
- Taeho Hwang
- Kijung Shin
date: '2023-11-01'
publishDate: '2024-09-13T09:52:58.667935Z'
publication_types:
- article-journal
abstract: Relations among multiple entities are prevalent in many fields, and hypergraphs
  are widely used to represent such group relations. Hence, machine learning on hypergraphs
  has received considerable attention, and especially much effort has been made in
  neural network architectures for hypergraphs (a.k.a., hypergraph neural networks).
  However, existing studies mostly focused on small datasets for a few single-entity-level
  downstream tasks and overlooked scalability issues, although most real-world group
  relations are large-scale. In this work, we propose new tasks, datasets, and scalable
  training methods for addressing these limitations. First, we introduce two pair-level
  hypergraph-learning tasks to formulate a wide range of real-world problems. Then,
  we build and publicly release two large-scale hypergraph datasets with tens of millions
  of nodes, rich features, and labels. After that, we propose PCL, a scalable learning
  method for hypergraph neural networks. To tackle scalability issues, PCL splits
  a given hypergraph into partitions and trains a neural network via contrastive learning.
  Our extensive experiments demonstrate that hypergraph neural networks can be trained
  for large-scale hypergraphs by PCL while outperforming 16 baseline models. Specifically,
  the performance is comparable, or surprisingly even better than that achieved by
  training hypergraph neural networks on the entire hypergraphs without partitioning.
tags:
- Contrastive learning
- Hypergraph neural networks
- Large-scale hypergraph datasets
- Partitioning
- Scalable hypergraph learning
links:
- name: URL
  url: https://doi.org/10.1007/s10618-023-00952-6
---