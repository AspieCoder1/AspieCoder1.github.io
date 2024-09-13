---
title: 'DisenHAN: Disentangled Heterogeneous Graph Attention Network for Recommendation'
authors:
- Yifan Wang
- Suyao Tang
- Yuntong Lei
- Weiping Song
- Sheng Wang
- Ming Zhang
date: '2020-10-19'
publishDate: '2024-09-13T09:52:59.462643Z'
publication_types:
- manuscript
publication: '*Proceedings of the 29th ACM International Conference on Information
  & Knowledge Management*'
abstract: Heterogeneous information network has been widely used to alleviate sparsity
  and cold start problems in recommender systems since it can model rich context information
  in user-item interactions. Graph neural network is able to encode this rich context
  information through propagation on the graph. However, existing heterogeneous graph
  neural networks neglect entanglement of the latent factors stemming from different
  aspects. Moreover, meta paths in existing approaches are simplified as connecting
  paths or side information between node pairs, overlooking the rich semantic information
  in the paths. In this paper, we propose a novel disentangled heterogeneous graph
  attention network DisenHAN for top-$N$ recommendation, which learns disentangled
  user/item representations from different aspects in a heterogeneous information
  network. In particular, we use meta relations to decompose high-order connectivity
  between node pairs and propose a disentangled embedding propagation layer which
  can iteratively identify the major aspect of meta relations. Our model aggregates
  corresponding aspect features from each meta relation for the target user/item.
  With different layers of embedding propagation, DisenHAN is able to explicitly capture
  the collaborative filtering effect semantically. Extensive experiments on three
  real-world datasets show that DisenHAN consistently outperforms state-of-the-art
  approaches. We further demonstrate the effectiveness and interpretability of the
  learned disentangled representations via insightful case studies and visualization.
tags:
- Computer Science - Information Retrieval
- Computer Science - Machine Learning
- Computer Science - Social and Information Networks
links:
- name: URL
  url: http://arxiv.org/abs/2106.10879
---