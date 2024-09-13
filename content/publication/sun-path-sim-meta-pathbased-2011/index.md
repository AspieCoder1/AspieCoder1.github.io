---
title: 'PathSim: meta path-based top-K similarity search in heterogeneous information
  networks'
authors:
- Yizhou Sun
- Jiawei Han
- Xifeng Yan
- Philip S. Yu
- Tianyi Wu
date: '2011-08-01'
publishDate: '2024-09-13T09:52:59.318179Z'
publication_types:
- article-journal
abstract: Similarity search is a primitive operation in database and Web search engines.
  With the advent of large-scale heterogeneous information networks that consist of
  multi-typed, interconnected objects, such as the bibliographic networks and social
  media networks, it is important to study similarity search in such networks. Intuitively,
  two objects are similar if they are linked by many paths in the network. However,
  most existing similarity measures are defined for homogeneous networks. Different
  semantic meanings behind paths are not taken into consideration. Thus they cannot
  be directly applied to heterogeneous networks.In this paper, we study similarity
  search that is defined among the same type of objects in heterogeneous networks.
  Moreover, by considering different linkage paths in a network, one could derive
  various similarity semantics. Therefore, we introduce the concept of meta path-based
  similarity, where a meta path is a path consisting of a sequence of relations defined
  between different object types (i.e., structural paths at the meta level). No matter
  whether a user would like to explicitly specify a path combination given sufficient
  domain knowledge, or choose the best path by experimental trials, or simply provide
  training examples to learn it, meta path forms a common base for a network-based
  similarity search engine. In particular, under the meta path framework we define
  a novel similarity measure called PathSim that is able to find peer objects in the
  network (e.g., find authors in the similar field and with similar reputation), which
  turns out to be more meaningful in many scenarios compared with random-walk based
  similarity measures. In order to support fast online query processing for PathSim
  queries, we develop an efficient solution that partially materializes short meta
  paths and then concatenates them online to compute top-k results. Experiments on
  real data sets demonstrate the effectiveness and efficiency of our proposed paradigm.
links:
- name: URL
  url: https://doi.org/10.14778/3402707.3402736
---