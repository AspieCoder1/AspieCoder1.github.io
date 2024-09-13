---
title: Towards Self-Explainable Graph Neural Network
authors:
- Enyan Dai
- Suhang Wang
date: '2021-08-26'
publishDate: '2024-09-13T09:52:58.048351Z'
publication_types:
- manuscript
abstract: Graph Neural Networks (GNNs), which generalize the deep neural networks
  to graph-structured data, have achieved great success in modeling graphs. However,
  as an extension of deep learning for graphs, GNNs lack explainability, which largely
  limits their adoption in scenarios that demand the transparency of models. Though
  many efforts are taken to improve the explainability of deep learning, they mainly
  focus on i.i.d data, which cannot be directly applied to explain the predictions
  of GNNs because GNNs utilize both node features and graph topology to make predictions.
  There are only very few work on the explainability of GNNs and they focus on post-hoc
  explanations. Since post-hoc explanations are not directly obtained from the GNNs,
  they can be biased and misrepresent the true explanations. Therefore, in this paper,
  we study a novel problem of self-explainable GNNs which can simultaneously give
  predictions and explanations. We propose a new framework which can find $K$-nearest
  labeled nodes for each unlabeled node to give explainable node classification, where
  nearest labeled nodes are found by interpretable similarity module in terms of both
  node similarity and local structure similarity. Extensive experiments on real-world
  and synthetic datasets demonstrate the effectiveness of the proposed framework for
  explainable node classification.
tags:
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2108.12055
---
