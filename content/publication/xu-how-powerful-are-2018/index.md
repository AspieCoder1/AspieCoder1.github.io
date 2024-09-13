---
title: How Powerful are Graph Neural Networks?
authors:
- Keyulu Xu
- Weihua Hu
- Jure Leskovec
- Stefanie Jegelka
date: '2018-09-27'
publishDate: '2024-09-13T09:52:59.575611Z'
publication_types:
- paper-conference
abstract: Graph Neural Networks (GNNs) are an effective framework for representation
  learning of graphs. GNNs follow a neighborhood aggregation scheme, where the representation
  vector of a node is computed by recursively aggregating and transforming representation
  vectors of its neighboring nodes. Many GNN variants have been proposed and have
  achieved state-of-the-art results on both node and graph classification tasks. However,
  despite GNNs revolutionizing graph representation learning, there is limited understanding
  of their representational properties and limitations. Here, we present a theoretical
  framework for analyzing the expressive power of GNNs to capture different graph
  structures. Our results characterize the discriminative power of popular GNN variants,
  such as Graph Convolutional Networks and GraphSAGE, and show that they cannot learn
  to distinguish certain simple graph structures. We then develop a simple architecture
  that is provably the most expressive among the class of GNNs and is as powerful
  as the Weisfeiler-Lehman graph isomorphism test. We empirically validate our theoretical
  findings on a number of graph classification benchmarks, and demonstrate that our
  model achieves state-of-the-art performance.
links:
- name: URL
  url: https://openreview.net/forum?id=ryGs6iA5Km
---
