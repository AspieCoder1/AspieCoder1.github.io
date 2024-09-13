---
title: 'Beyond Homophily in Graph Neural Networks: Current Limitations and Effective
  Designs'
authors:
- Jiong Zhu
- Yujun Yan
- Lingxiao Zhao
- Mark Heimann
- Leman Akoglu
- Danai Koutra
date: '2020-01-01'
publishDate: '2024-09-13T09:52:59.804911Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems*'
abstract: We investigate the representation power of graph neural networks in the
  semi-supervised node classification task under heterophily or low homophily, i.e.,
  in networks where connected nodes may have different class labels and dissimilar
  features. Many popular GNNs fail to generalize to this setting, and are even outperformed
  by models that ignore the graph structure (e.g., multilayer perceptrons). Motivated
  by this limitation, we identify a set of key designs—ego- and neighbor-embedding
  separation, higher-order neighborhoods, and combination of intermediate representations—that
  boost learning from the graph structure under heterophily. We combine them into
  a graph neural network, H2GCN, which we use as the base method to empirically evaluate
  the effectiveness of the identified designs. Going beyond the traditional benchmarks
  with strong homophily, our empirical analysis shows that the identified designs
  increase the accuracy of GNNs by up to 40% and 27% over models without them on synthetic
  and real networks with heterophily, respectively, and yield competitive performance
  under homophily.
links:
- name: URL
  url: 
    https://proceedings.neurips.cc/paper/2020/hash/58ae23d878a47004366189884c2f8440-Abstract.html
---
