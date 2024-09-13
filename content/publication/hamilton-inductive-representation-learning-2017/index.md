---
title: Inductive Representation Learning on Large Graphs
authors:
- Will Hamilton
- Zhitao Ying
- Jure Leskovec
date: '2017-01-01'
publishDate: '2024-09-13T09:52:58.415671Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems*'
abstract: "Low-dimensional embeddings of nodes in large graphs have proved extremely
  useful in a variety of prediction tasks, from content recommendation to identifying
  protein functions. However, most existing approaches require that all nodes in the
  graph are present during training of the embeddings; these previous approaches are
  inherently transductive and do not naturally generalize to unseen nodes. Here we
  present GraphSAGE, a general, inductive framework that leverages node feature information
  (e.g., text attributes) to efficiently generate node embeddings.  Instead of training
  individual embeddings for each node, we learn a function that generates embeddings
  by sampling and aggregating features from a node's local neighborhood. Our algorithm
  outperforms strong baselines on three inductive node-classification benchmarks:
  we classify the category of unseen nodes in evolving information graphs based on
  citation and Reddit post data, and we show that our algorithm generalizes to completely
  unseen graphs using a multi-graph dataset of protein-protein interactions."
links:
- name: URL
  url: 
    https://proceedings.neurips.cc/paper_files/paper/2017/hash/5dd9db5e033da9c6fb5ba83c7a7ebea9-Abstract.html
---
