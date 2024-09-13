---
title: On the Bottleneck of Graph Neural Networks and its Practical Implications
authors:
- Uri Alon
- Eran Yahav
date: '2020-10-02'
publishDate: '2024-09-13T09:52:57.677922Z'
publication_types:
- paper-conference
abstract: 'Since the proposal of the graph neural network (GNN) by Gori et al. (2005)
  and Scarselli et al. (2008), one of the major problems in training GNNs was their
  struggle to propagate information between distant nodes in the graph. We propose
  a new explanation for this problem: GNNs are susceptible to a bottleneck when aggregating
  messages across a long path. This bottleneck causes the over-squashing of exponentially
  growing information into fixed-size vectors. As a result, GNNs fail to propagate
  messages originating from distant nodes and perform poorly when the prediction task
  depends on long-range interaction. In this paper, we highlight the inherent problem
  of over-squashing in GNNs: we demonstrate that the bottleneck hinders popular GNNs
  from fitting long-range signals in the training data; we further show that GNNs
  that absorb incoming edges equally, such as GCN and GIN, are more susceptible to
  over-squashing than GAT and GGNN; finally, we show that prior work, which extensively
  tuned GNN models of long-range problems, suffers from over-squashing, and that breaking
  the bottleneck improves their state-of-the-art results without any tuning or additional
  weights. Our code is available at https://github.com/tech-srl/bottleneck/ .'
links:
- name: URL
  url: https://openreview.net/forum?id=i80OPhOCVH2
---