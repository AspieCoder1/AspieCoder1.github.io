---
title: On Explainability of Graph Neural Networks via Subgraph Explorations
authors:
- Hao Yuan
- Haiyang Yu
- Jie Wang
- Kang Li
- Shuiwang Ji
date: '2021-07-01'
publishDate: '2024-09-13T09:52:59.647420Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 38th International Conference on Machine Learning*'
abstract: We consider the problem of explaining the predictions of graph neural networks
  (GNNs), which otherwise are considered as black boxes. Existing methods invariably
  focus on explaining the importance of graph nodes or edges but ignore the substructures
  of graphs, which are more intuitive and human-intelligible. In this work, we propose
  a novel method, known as SubgraphX, to explain GNNs by identifying important subgraphs.
  Given a trained GNN model and an input graph, our SubgraphX explains its predictions
  by efficiently exploring different subgraphs with Monte Carlo tree search. To make
  the tree search more effective, we propose to use Shapley values as a measure of
  subgraph importance, which can also capture the interactions among different subgraphs.
  To expedite computations, we propose efficient approximation schemes to compute
  Shapley values for graph data. Our work represents the first attempt to explain
  GNNs via identifying subgraphs explicitly and directly. Experimental results show
  that our SubgraphX achieves significantly improved explanations, while keeping computations
  at a reasonable level.
links:
- name: URL
  url: https://proceedings.mlr.press/v139/yuan21c.html
---