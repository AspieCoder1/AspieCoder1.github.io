---
title: High-order pooling for graph neural networks with tensor decomposition
authors:
- Chenqing Hua
- Guillaume Rabusseau
- Jian Tang
date: '2022-01-01'
publishDate: '2024-09-13T09:52:58.523291Z'
publication_types:
- paper-conference
publication: '*Curran Associates Inc.*'
abstract: Graph Neural Networks (GNNs) are attracting growing attention due to their
  effectiveness and flexibility in modeling a variety of graph-structured data. Exiting
  GNN architectures usually adopt simple pooling operations (e.g., sum, average, max)
  when aggregating messages from a local neighborhood for updating node representation
  or pooling node representations from the entire graph to compute the graph representation.
  Though simple and effective, these linear operations do not model high-order non-linear
  interactions among nodes. We propose the Tensorized Graph Neural Network (tGNN),
  a highly expressive GNN architecture relying on tensor decomposition to model high-order
  non-linear node interactions. tGNN leverages the symmetric CP decomposition to efficiently
  parameterize permutation-invariant multilinear maps for modeling node interactions.
  Theoretical and empirical analysis on both node and graph classification tasks show
  the superiority of tGNN over competitive baselines. In particular, tGNN achieves
  the most solid results on two OGB node classification datasets and one OGB graph
  classification dataset.
---