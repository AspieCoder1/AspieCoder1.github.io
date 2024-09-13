---
title: 'Sheaf4Rec: Sheaf Neural Networks for Graph-based Recommender Systems'
authors:
- Antonio Purificato
- Giulia Cassarà
- Federico Siciliano
- Pietro Liò
- Fabrizio Silvestri
date: '2024-03-16'
publishDate: '2024-09-13T09:52:59.033202Z'
publication_types:
- manuscript
abstract: 'Recent advancements in Graph Neural Networks (GNN) have facilitated their
  widespread adoption in various applications, including recommendation systems. GNNs
  have proven to be effective in addressing the challenges posed by recommendation
  systems by efficiently modeling graphs in which nodes represent users or items and
  edges denote preference relationships. However, current GNN techniques represent
  nodes by means of a single static vector, which may inadequately capture the intricate
  complexities of users and items. To overcome these limitations, we propose a solution
  integrating a cutting-edge model inspired by category theory: Sheaf4Rec. Unlike
  single vector representations, Sheaf Neural Networks and their corresponding Laplacians
  represent each node (and edge) using a vector space. Our approach takes advantage
  from this theory and results in a more comprehensive representation that can be
  effectively exploited during inference, providing a versatile method applicable
  to a wide range of graph-related tasks and demonstrating unparalleled performance.
  Our proposed model exhibits a noteworthy relative improvement of up to 8.53% on
  F1-Score@10 and an impressive increase of up to 11.29% on NDCG@10, outperforming
  existing state-of-the-art models such as Neural Graph Collaborative Filtering (NGCF),
  KGTORe and other recently developed GNN-based models. In addition to its superior
  predictive capabilities, Sheaf4Rec shows remarkable improvements in terms of efficiency:
  we observe substantial runtime improvements ranging from 2.5% up to 37% when compared
  to other GNN-based competitor models, indicating a more efficient way of handling
  information while achieving better performance. Code is available at https://github.com/antoniopurificato/Sheaf4Rec.'
tags:
- '55'
- Computer Science - Information Retrieval
- Computer Science - Machine Learning
- H.3.3
- I.2.6
links:
- name: URL
  url: http://arxiv.org/abs/2304.09097
---