---
title: Are we really making much progress? Revisiting, benchmarking and refining heterogeneous
  graph neural networks
authors:
- Qingsong Lv
- Ming Ding
- Qiang Liu
- Yuxiang Chen
- Wenzheng Feng
- Siming He
- Chang Zhou
- Jianguo Jiang
- Yuxiao Dong
- Jie Tang
date: '2021-08-14'
publishDate: '2024-09-13T09:52:58.849593Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery
  & Data Mining*'
abstract: Heterogeneous graph neural networks (HGNNs) have been blossoming in recent
  years, but the unique data processing and evaluation setups used by each work obstruct
  a full understanding of their advancements. In this work, we present a systematical
  reproduction of 12 recent HGNNs by using their official codes, datasets, settings,
  and hyperparameters, revealing surprising findings about the progress of HGNNs.
  We find that the simple homogeneous GNNs, e.g., GCN and GAT, are largely underestimated
  due to improper settings. GAT with proper inputs can generally match or outperform
  all existing HGNNs across various scenarios. To facilitate robust and reproducible
  HGNN research, we construct the Heterogeneous Graph Benchmark (HGB) , consisting
  of 11 diverse datasets with three tasks. HGB standardizes the process of heterogeneous
  graph data splits, feature processing, and performance evaluation. Finally, we introduce
  a simple but very strong baseline Simple-HGN-which significantly outperforms all
  previous models on HGB-to accelerate the advancement of HGNNs in the future.
links:
- name: URL
  url: https://doi.org/10.1145/3447548.3467350
---
