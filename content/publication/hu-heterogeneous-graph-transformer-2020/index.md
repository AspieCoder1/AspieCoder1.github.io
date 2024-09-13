---
title: Heterogeneous Graph Transformer
authors:
- Ziniu Hu
- Yuxiao Dong
- Kuansan Wang
- Yizhou Sun
date: '2020-03-02'
publishDate: '2024-09-13T09:52:58.566336Z'
publication_types:
- manuscript
abstract: Recent years have witnessed the emerging success of graph neural networks
  (GNNs) for modeling structured data. However, most GNNs are designed for homogeneous
  graphs, in which all nodes and edges belong to the same types, making them infeasible
  to represent heterogeneous structures. In this paper, we present the Heterogeneous
  Graph Transformer (HGT) architecture for modeling Web-scale heterogeneous graphs.
  To model heterogeneity, we design node- and edge-type dependent parameters to characterize
  the heterogeneous attention over each edge, empowering HGT to maintain dedicated
  representations for different types of nodes and edges. To handle dynamic heterogeneous
  graphs, we introduce the relative temporal encoding technique into HGT, which is
  able to capture the dynamic structural dependency with arbitrary durations. To handle
  Web-scale graph data, we design the heterogeneous mini-batch graph sampling algorithm---HGSampling---for
  efficient and scalable training. Extensive experiments on the Open Academic Graph
  of 179 million nodes and 2 billion edges show that the proposed HGT model consistently
  outperforms all the state-of-the-art GNN baselines by 9%--21% on various downstream
  tasks.
tags:
- Computer Science - Machine Learning
- Computer Science - Social and Information Networks
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2003.01332
---
