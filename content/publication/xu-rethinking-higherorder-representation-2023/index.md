---
title: Rethinking Higher-order Representation Learning with Graph Neural Networks
authors:
- Tuo Xu
- Lei Zou
date: '2023-11-25'
publishDate: '2024-09-13T09:52:59.589344Z'
publication_types:
- paper-conference
abstract: In the field of graph machine learning, graph neural networks (GNNs) are
  promising models for learning graph representations and node representations. However,
  many GNNs perform poorly on learning higher-order representations such as links
  due to their limited expressive power. Zhang et al. summarize recent advances in
  link prediction and propose labeling trick as a common framework for learning node
  set representations with GNNs. However, their theory is limited to employing an
  ideally expressive GNN as the backend, and can only justify a limited series of
  link prediction models. In this paper, we take a further step to study the expressive
  power of various higher-order representation learning methods. Our analysis begins
  with showing the inherent symmetry between node labeling and higher-order GNNs,
  which directly justifies previous labeling trick methods (SEAL, GraIL) and other
  node labeling methods (ID-GNN, NBFNet), also higher-order GNNs through a unfied
  framework. Then, we study the utilization of MPNNs for computing representations
  in these methods, and show the expressive power upper bounds under these situations.
  After that, we provide a comprehensive analysis about how these previous methods
  surpass plain GNNs by showing their ability to capture path information. Finally,
  using the intuitions provided by the analysis, we propose an extremely simple method
  for link prediction tasks, which we believe could bring insights for designing more
  complicated and powerful models in the future.
links:
- name: URL
  url: https://openreview.net/forum?id=2OyoYw4InI
---
