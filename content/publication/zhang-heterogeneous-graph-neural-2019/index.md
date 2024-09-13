---
title: Heterogeneous Graph Neural Network
authors:
- Chuxu Zhang
- Dongjin Song
- Chao Huang
- Ananthram Swami
- Nitesh V. Chawla
date: '2019-07-25'
publishDate: '2024-09-13T09:52:59.732208Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 25th ACM SIGKDD International Conference on Knowledge
  Discovery & Data Mining*'
abstract: Representation learning in heterogeneous graphs aims to pursue a meaningful
  vector representation for each node so as to facilitate downstream applications
  such as link prediction, personalized recommendation, node classification, etc.
  This task, however, is challenging not only because of the demand to incorporate
  heterogeneous structural (graph) information consisting of multiple types of nodes
  and edges, but also due to the need for considering heterogeneous attributes or
  contents (e.g., text or image) associated with each node. Despite a substantial
  amount of effort has been made to homogeneous (or heterogeneous) graph embedding,
  attributed graph embedding as well as graph neural networks, few of them can jointly
  consider heterogeneous structural (graph) information as well as heterogeneous contents
  information of each node effectively. In this paper, we propose HetGNN, a heterogeneous
  graph neural network model, to resolve this issue. Specifically, we first introduce
  a random walk with restart strategy to sample a fixed size of strongly correlated
  heterogeneous neighbors for each node and group them based upon node types. Next,
  we design a neural network architecture with two modules to aggregate feature information
  of those sampled neighboring nodes. The first module encodes \"deep\" feature interactions
  of heterogeneous contents and generates content embedding for each node. The second
  module aggregates content (attribute) embeddings of different neighboring groups
  (types) and further combines them by considering the impacts of different groups
  to obtain the ultimate node embedding. Finally, we leverage a graph context loss
  and a mini-batch gradient descent procedure to train the model in an end-to-end
  manner. Extensive experiments on several datasets demonstrate that HetGNN can outperform
  state-of-the-art baselines in various graph mining tasks, i.e., link prediction,
  recommendation, node classification & clustering and inductive node classification
  & clustering.
tags:
- graph embedding
- graph neural networks
- heterogeneous graphs
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3292500.3330961
---