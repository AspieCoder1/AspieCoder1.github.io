---
title: 'XGNN: Towards Model-Level Explanations of Graph Neural Networks'
authors:
- Hao Yuan
- Jiliang Tang
- Xia Hu
- Shuiwang Ji
date: '2020-08-20'
publishDate: '2024-09-13T09:52:59.668860Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 26th ACM SIGKDD International Conference on Knowledge
  Discovery & Data Mining*'
abstract: Graphs neural networks (GNNs) learn node features by aggregating and combining
  neighbor information, which have achieved promising performance on many graph tasks.
  However, GNNs are mostly treated as black-boxes and lack human intelligible explanations.
  Thus, they cannot be fully trusted and used in certain application domains if GNN
  models cannot be explained. In this work, we propose a novel approach, known as
  XGNN, to interpret GNNs at the model-level. Our approach can provide high-level
  insights and generic understanding of how GNNs work. In particular, we propose to
  explain GNNs by training a graph generator so that the generated graph patterns
  maximize a certain prediction of the model. We formulate the graph generation as
  a reinforcement learning task, where for each step, the graph generator predicts
  how to add an edge into the current graph. The graph generator is trained via a
  policy gradient method based on information from the trained GNNs. In addition,
  we incorporate several graph rules to encourage the generated graphs to be valid.
  Experimental results on both synthetic and real-world datasets show that our proposed
  methods help understand and verify the trained GNNs. Furthermore, our experimental
  results indicate that the generated graphs can provide guidance on how to improve
  the trained GNNs.
tags:
- deep learning
- graph neural networks
- interpretability
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3394486.3403085
---