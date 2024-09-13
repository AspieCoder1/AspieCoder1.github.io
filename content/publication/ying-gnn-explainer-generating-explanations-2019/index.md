---
title: 'GNNExplainer: Generating Explanations for Graph Neural Networks'
authors:
- Zhitao Ying
- Dylan Bourgeois
- Jiaxuan You
- Marinka Zitnik
- Jure Leskovec
date: '2019-01-01'
publishDate: '2024-09-13T09:52:59.640200Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems*'
abstract: Graph Neural Networks (GNNs) are a powerful tool for machine learning on
  graphs.GNNs combine node feature information with the graph structure by  recursively
  passing neural messages along edges of the input graph. However, incorporating both
  graph structure and feature information leads to complex models, and explaining
  predictions made by GNNs remains unsolved. Here we propose GNNExplainer, the first
  general, model-agnostic approach for providing interpretable explanations for predictions
  of any GNN-based model on any graph-based machine learning task. Given an instance,
  GNNExplainer identifies a compact subgraph structure and a small subset of node
  features that have a crucial role in GNN's prediction.  Further, GNNExplainer  can
  generate consistent and concise explanations for an entire class of instances. We
  formulate GNNExplainer as an optimization task that maximizes the mutual information
  between a GNN's prediction and distribution of possible subgraph structures. Experiments
  on synthetic and real-world graphs show that our approach can identify important
  graph structures as well as node features, and outperforms baselines by 17.1% on
  average. GNNExplainer  provides a variety of benefits, from the ability to visualize
  semantically relevant structures to interpretability, to giving insights into errors
  of faulty GNNs.
links:
- name: URL
  url: 
    https://proceedings.neurips.cc/paper_files/paper/2019/hash/d80b7040b773199015de6d3b4293c8ff-Abstract.html
---
