---
title: Distilling the Knowledge in a Neural Network
authors:
- Geoffrey Hinton
- Oriol Vinyals
- Jeff Dean
date: '2015-03-09'
publishDate: '2024-09-13T09:52:58.470326Z'
publication_types:
- manuscript
abstract: A very simple way to improve the performance of almost any machine learning
  algorithm is to train many different models on the same data and then to average
  their predictions. Unfortunately, making predictions using a whole ensemble of models
  is cumbersome and may be too computationally expensive to allow deployment to a
  large number of users, especially if the individual models are large neural nets.
  Caruana and his collaborators have shown that it is possible to compress the knowledge
  in an ensemble into a single model which is much easier to deploy and we develop
  this approach further using a different compression technique. We achieve some surprising
  results on MNIST and we show that we can significantly improve the acoustic model
  of a heavily used commercial system by distilling the knowledge in an ensemble of
  models into a single model. We also introduce a new type of ensemble composed of
  one or more full models and many specialist models which learn to distinguish fine-grained
  classes that the full models confuse. Unlike a mixture of experts, these specialist
  models can be trained rapidly and in parallel.
tags:
- Computer Science - Machine Learning
- Computer Science - Neural and Evolutionary Computing
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/1503.02531
---