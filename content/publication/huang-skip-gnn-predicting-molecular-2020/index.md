---
title: 'SkipGNN: predicting molecular interactions with skip-graph networks'
authors:
- Kexin Huang
- Cao Xiao
- Lucas M. Glass
- Marinka Zitnik
- Jimeng Sun
date: '2020-12-03'
publishDate: '2024-09-13T09:52:58.544140Z'
publication_types:
- article-journal
publication: '*Nature Publishing Group*'
abstract: Molecular interaction networks are powerful resources for molecular discovery.
  They are increasingly used with machine learning methods to predict biologically
  meaningful interactions. While deep learning on graphs has dramatically advanced
  the prediction prowess, current graph neural network (GNN) methods are mainly optimized
  for prediction on the basis of direct similarity between interacting nodes. In biological
  networks, however, similarity between nodes that do not directly interact has proved
  incredibly useful in the last decade across a variety of interaction networks. Here,
  we present SkipGNN, a graph neural network approach for the prediction of molecular
  interactions. SkipGNN predicts molecular interactions by not only aggregating information
  from direct interactions but also from second-order interactions, which we call
  skip similarity. In contrast to existing GNNs, SkipGNN receives neural messages
  from two-hop neighbors as well as immediate neighbors in the interaction network
  and non-linearly transforms the messages to obtain useful information for prediction.
  To inject skip similarity into a GNN, we construct a modified version of the original
  network, called the skip graph. We then develop an iterative fusion scheme that
  optimizes a GNN using both the skip graph and the original graph. Experiments on
  four interaction networks, including drug–drug, drug–target, protein–protein, and
  gene–disease interactions, show that SkipGNN achieves superior and robust performance.
  Furthermore, we show that unlike popular GNNs, SkipGNN learns biologically meaningful
  embeddings and performs especially well on noisy, incomplete interaction networks.
tags:
- Biochemical reaction networks
- Computational models
- Data mining
- Machine learning
links:
- name: URL
  url: https://www.nature.com/articles/s41598-020-77766-9
---
