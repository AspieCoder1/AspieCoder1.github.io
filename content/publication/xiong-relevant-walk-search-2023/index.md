---
title: Relevant Walk Search for Explaining Graph Neural Networks
authors:
- Ping Xiong
- Thomas Schnake
- Michael Gastegger
- Grégoire Montavon
- Klaus Robert Muller
- Shinichi Nakajima
date: '2023-07-03'
publishDate: '2024-09-13T09:52:59.568397Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 40th International Conference on Machine Learning*'
abstract: Graph Neural Networks (GNNs) have become important machine learning tools
  for graph analysis, and its explainability is crucial for safety, fairness, and
  robustness. Layer-wise relevance propagation for GNNs (GNN-LRP) evaluates the relevance
  of walks to reveal important information flows in the network, and provides higher-order
  explanations, which have been shown to be superior to the lower-order, i.e., node-/edge-level,
  explanations. However, identifying relevant walks by GNN-LRP requires exponential
  computational complexity with respect to the network depth, which we will remedy
  in this paper. Specifically, we propose polynomial-time algorithms for finding top-$K$
  relevant walks, which drastically reduces the computation and thus increases the
  applicability of GNN-LRP to large-scale problems. Our proposed algorithms are based
  on the max-product algorithm—a common tool for finding the maximum likelihood configurations
  in probabilistic graphical models—and can find the most relevant walks exactly at
  the neuron level and approximately at the node level. Our experiments demonstrate
  the performance of our algorithms at scale and their utility across application
  domains, i.e., on epidemiology, molecular, and natural language benchmarks. We provide
  our codes under github.com/xiong-ping/rel_walk_gnnlrp.
links:
- name: URL
  url: https://proceedings.mlr.press/v202/xiong23b.html
---
