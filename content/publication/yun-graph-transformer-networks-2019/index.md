---
title: Graph Transformer Networks
authors:
- Seongjun Yun
- Minbyul Jeong
- Raehyun Kim
- Jaewoo Kang
- Hyunwoo J Kim
date: '2019-01-01'
publishDate: '2024-09-13T09:52:59.683976Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems*'
abstract: Graph neural networks (GNNs) have been widely used in representation learning
  on graphs and achieved state-of-the-art performance in tasks such as node classification
  and link prediction. However, most existing GNNs are designed to learn node representations
  on the fixed and homogeneous graphs. The limitations especially become problematic
  when learning representations on a misspecified graph or a heterogeneous graph that
  consists of various types of nodes and edges. In this paper, we propose Graph Transformer
  Networks (GTNs) that are capable of generating new graph structures, which involve
  identifying useful connections between unconnected nodes on the original graph,
  while learning effective node representation on the new graphs in an end-to-end
  fashion. Graph Transformer layer, a core layer of GTNs, learns a soft selection
  of edge types and composite relations for generating useful multi-hop connections
  so-call meta-paths. Our experiments show that GTNs learn new graph structures, based
  on data and tasks without domain knowledge, and yield powerful node representation
  via convolution on the new graphs. Without domain-specific graph preprocessing,
  GTNs achieved the best performance in all three benchmark node classification tasks
  against the state-of-the-art methods that require pre-defined meta-paths from domain
  knowledge.
links:
- name: URL
  url: 
    https://proceedings.neurips.cc/paper_files/paper/2019/hash/9d63484abb477c97640154d40595a3bb-Abstract.html
---
