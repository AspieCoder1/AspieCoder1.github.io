---
title: 'UltraGCN: Ultra Simplification of Graph Convolutional Networks for Recommendation'
authors:
- Kelong Mao
- Jieming Zhu
- Xi Xiao
- Biao Lu
- Zhaowei Wang
- Xiuqiang He
date: '2021-10-30'
publishDate: '2024-09-13T09:52:58.885402Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 30th ACM International Conference on Information
  & Knowledge Management*'
abstract: With the recent success of graph convolutional networks (GCNs), they have
  been widely applied for recommendation, and achieved impressive performance gains.
  The core of GCNs lies in its message passing mechanism to aggregate neighborhood
  information. However, we observed that message passing largely slows down the convergence
  of GCNs during training, especially for large-scale recommender systems, which hinders
  their wide adoption. LightGCN makes an early attempt to simplify GCNs for collaborative
  filtering by omitting feature transformations and nonlinear activations. In this
  paper, we take one step further to propose an ultra-simplified formulation of GCNs
  (dubbed UltraGCN), which skips infinite layers of message passing for efficient
  recommendation. Instead of explicit message passing, UltraGCN resorts to directly
  approximate the limit of infinite-layer graph convolutions via a constraint loss.
  Meanwhile, UltraGCN allows for more appropriate edge weight assignments and flexible
  adjustment of the relative importances among different types of relationships. This
  finally yields a simple yet effective UltraGCN model, which is easy to implement
  and efficient to train. Experimental results on four benchmark datasets show that
  UltraGCN not only outperforms the state-of-the-art GCN models but also achieves
  more than 10x speedup over LightGCN.
tags:
- collaborative filtering
- graph convolutional networks
- recommender systems
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3459637.3482291
---