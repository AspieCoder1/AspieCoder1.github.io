---
title: Interpreting Graph Neural Networks for NLP With Differentiable Edge Masking
authors:
- Michael Sejr Schlichtkrull
- Nicola De Cao
- Ivan Titov
date: '2021-01-01'
publishDate: '2024-09-13T09:52:59.178533Z'
publication_types:
- paper-conference
abstract: Graph neural networks (GNNs) have become a popular approach to integrating
  structural inductive biases into NLP models. However, there has been little work
  on interpreting them, and specifically on understanding which parts of the graphs
  (e.g. syntactic trees or co-reference structures) contribute to a prediction. In
  this work, we introduce a post-hoc method for interpreting the predictions of GNNs
  which identifies unnecessary edges. Given a trained GNN model, we learn a simple
  classifier that, for every edge in every layer, predicts if that edge can be dropped.
  We demonstrate that such a classifier can be trained in a fully differentiable fashion,
  employing stochastic gates and encouraging sparsity through the expected $L_0$ norm.
  We use our technique as an attribution method to analyze GNN models for two tasks
  -- question answering and semantic role labeling -- providing insights into the
  information flow in these models. We show that we can drop a large proportion of
  edges without deteriorating the performance of the model, while we can analyse the
  remaining edges for interpreting model predictions.
links:
- name: URL
  url: https://openreview.net/forum?id=WznmQa42ZAx
---