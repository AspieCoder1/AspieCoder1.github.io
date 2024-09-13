---
title: Predicting Path Failure In Time-Evolving Graphs
authors:
- Jia Li
- Zhichao Han
- Hong Cheng
- Jiao Su
- Pengyun Wang
- Jianfeng Zhang
- Lujia Pan
date: '2019-07-25'
publishDate: '2024-09-13T09:52:58.813424Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 25th ACM SIGKDD International Conference on Knowledge
  Discovery & Data Mining*'
abstract: In this paper we use a time-evolving graph which consists of a sequence
  of graph snapshots over time to model many real-world networks. We study the path
  classification problem in a time-evolving graph, which has many applications in
  real-world scenarios, for example, predicting path failure in a telecommunication
  network and predicting path congestion in a traffic network in the near future.
  In order to capture the temporal dependency and graph structure dynamics, we design
  a novel deep neural network named Long Short-Term Memory R-GCN (LRGCN). LRGCN considers
  temporal dependency between time-adjacent graph snapshots as a special relation
  with memory, and uses relational GCN to jointly process both intra-time and inter-time
  relations. We also propose a new path representation method named self-attentive
  path embedding (SAPE), to embed paths of arbitrary length into fixed-length vectors.
  Through experiments on a real-world telecommunication network and a traffic network
  in California, we demonstrate the superiority of LRGCN to other competing methods
  in path failure prediction, and prove the effectiveness of SAPE on path representation.
tags:
- classification
- path representation
- time-evolving graph
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3292500.3330847
---
