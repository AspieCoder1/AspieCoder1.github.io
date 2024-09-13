---
title: Session-Based Recommendation with Graph Neural Networks for Repeat Consumption
authors:
- Gang Yang
- Xiaofeng Zhang
- Yueping Li
date: '2021-01-11'
publishDate: '2024-09-13T09:52:59.625822Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2020 9th International Conference on Computing and
  Pattern Recognition*'
abstract: Session-based recommendation aims to predict user actions only based on
  anonymous session sequence. The repeat consumption is a common phenomenon in the
  recommendation scenarios which the items will be clicked repeatedly many times.
  Existing recommended methods for session-based repeat consumption model a session
  as sequence and use Markov Chain (MC) or Recurrent Neural Network (RNNs) to generate
  the representations of items. Although achieved promising results, these models
  still have the deficiencies in obtaining the correct user vectors and complex transitions
  of items. On the other hand, the number of unclicked items is very large relative
  to the items that have been clicked in a session, that it is more difficult to mine
  information for unclicked items. In this paper, we proposed an improved model named
  GNN-RepeatNet based on RepeatNet to explicitly model the repeat consumptions in
  session-based recommendation, by utilizing the graph neural network and multi-layer
  self-attention. In GNN-RepeatNet, we get accurate item embedding and complex transitions
  of items via graph neural network (GNN). Then through a repeat-explore mechanism,
  we compute the probabilities of predicted items in repeat mode and deep-explore
  mode separately. In addition, the multi-layer self-attention networks is introduced
  to deeply explore the unclicked items in deep-explore model. Extensive experiments
  conducted on two real datasets show that GNN-RepeatNet can improve the performance
  compared to the state-of-the-art methods.
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3436369.3436454
---
