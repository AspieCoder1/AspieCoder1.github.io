---
title: Practical Bayesian Optimization of Machine Learning Algorithms
authors:
- Jasper Snoek
- Hugo Larochelle
- Ryan P. Adams
date: '2012-08-29'
publishDate: '2024-09-13T09:52:59.276525Z'
publication_types:
- manuscript
abstract: Machine learning algorithms frequently require careful tuning of model hyperparameters,
  regularization terms, and optimization parameters. Unfortunately, this tuning is
  often a \"black art\" that requires expert experience, unwritten rules of thumb,
  or sometimes brute-force search. Much more appealing is the idea of developing automatic
  approaches which can optimize the performance of a given learning algorithm to the
  task at hand. In this work, we consider the automatic tuning problem within the
  framework of Bayesian optimization, in which a learning algorithm's generalization
  performance is modeled as a sample from a Gaussian process (GP). The tractable posterior
  distribution induced by the GP leads to efficient use of the information gathered
  by previous experiments, enabling optimal choices about what parameters to try next.
  Here we show how the effects of the Gaussian process prior and the associated inference
  procedure can have a large impact on the success or failure of Bayesian optimization.
  We show that thoughtful choices can lead to results that exceed expert-level performance
  in tuning machine learning algorithms. We also describe new algorithms that take
  into account the variable cost (duration) of learning experiments and that can leverage
  the presence of multiple cores for parallel experimentation. We show that these
  proposed algorithms improve on previous automatic procedures and can reach or surpass
  human expert-level optimization on a diverse set of contemporary algorithms including
  latent Dirichlet allocation, structured SVMs and convolutional neural networks.
tags:
- Computer Science - Machine Learning
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/1206.2944
---