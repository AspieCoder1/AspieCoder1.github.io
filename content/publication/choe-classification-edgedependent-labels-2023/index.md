---
title: Classification of Edge-dependent Labels of Nodes in Hypergraphs
authors:
- Minyoung Choe
- Sunwoo Kim
- Jaemin Yoo
- Kijung Shin
date: '2023-08-04'
publishDate: '2024-09-13T09:52:57.976501Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery
  and Data Mining*'
abstract: A hypergraph is a data structure composed of nodes and hyperedges, where
  each hyperedge is an any-sized subset of nodes. Due to the flexibility in hyperedge
  size, hypergraphs represent group interactions (e.g., co-authorship by more than
  two authors) more naturally and accurately than ordinary graphs. Interestingly,
  many real-world systems modeled as hypergraphs contain edge-dependent node labels,
  i.e., node labels that vary depending on hyperedges. For example, on co-authorship
  datasets, the same author (i.e., a node) can be the primary author in a paper (i.e.,
  a hyperedge) but the corresponding author in another paper (i.e., another hyperedge).
  In this work, we introduce a classification of edge-dependent node labels as a new
  problem. This problem can be used as a benchmark task for hypergraph neural networks,
  which recently have attracted great attention, and also the usefulness of edge-dependent
  node labels has been verified in various applications. To tackle this problem, we
  propose WHATsNet, a novel hypergraph neural network that represents the same node
  differently depending on the hyperedges it participates in by reflecting its varying
  importance in the hyperedges. To this end, WHATsNet models the relations between
  nodes within each hyperedge, using their relative centrality as positional encodings.
  In our experiments, we demonstrate that WHATsNet significantly and consistently
  outperforms ten competitors on six real-world hypergraphs, and we also show successful
  applications of WHATsNet to (a) ranking aggregation, (b) node clustering, and (c)
  product return prediction.
tags:
- edge-dependent node label
- graph neural network
- hypergraph
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3580305.3599274
---