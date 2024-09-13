---
title: 'EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs'
authors:
- Aldo Pareja
- Giacomo Domeniconi
- Jie Chen
- Tengfei Ma
- Toyotaro Suzumura
- Hiroki Kanezashi
- Tim Kaler
- Tao Schardl
- Charles Leiserson
date: '2020-04-03'
publishDate: '2024-09-13T09:52:59.003221Z'
publication_types:
- article-journal
abstract: Graph representation learning resurges as a trending research subject owing
  to the widespread use of deep learning for Euclidean data, which inspire various
  creative designs of neural networks in the non-Euclidean domain, particularly graphs.
  With the success of these graph neural networks (GNN) in the static setting, we
  approach further practical scenarios where the graph dynamically evolves. Existing
  approaches typically resort to node embeddings and use a recurrent neural network
  (RNN, broadly speaking) to regulate the embeddings and learn the temporal dynamics.
  These methods require the knowledge of a node in the full time span (including both
  training and testing) and are less applicable to the frequent change of the node
  set. In some extreme scenarios, the node sets at different time steps may completely
  differ. To resolve this challenge, we propose EvolveGCN, which adapts the graph
  convolutional network (GCN) model along the temporal dimension without resorting
  to node embeddings. The proposed approach captures the dynamism of the graph sequence
  through using an RNN to evolve the GCN parameters. Two architectures are considered
  for the parameter evolution. We evaluate the proposed approach on tasks including
  link prediction, edge classification, and node classification. The experimental
  results indicate a generally higher performance of EvolveGCN compared with related
  approaches. The code is available at https://github.com/IBM/EvolveGCN.
links:
- name: URL
  url: https://ojs.aaai.org/index.php/AAAI/article/view/5984
---