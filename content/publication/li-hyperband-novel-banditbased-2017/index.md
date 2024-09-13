---
title: 'Hyperband: a novel bandit-based approach to hyperparameter optimization'
authors:
- Lisha Li
- Kevin Jamieson
- Giulia DeSalvo
- Afshin Rostamizadeh
- Ameet Talwalkar
date: '2017-01-01'
publishDate: '2024-09-13T09:52:58.799492Z'
publication_types:
- article-journal
abstract: Performance of machine learning algorithms depends critically on identifying
  a good set of hyperparameters. While recent approaches use Bayesian optimization
  to adaptively select configurations, we focus on speeding up random search through
  adaptive resource allocation and early-stopping. We formulate hyperparameter optimization
  as a pure-exploration nonstochastic infinite-armed bandit problem where a predefined
  resource like iterations, data samples, or features is allocated to randomly sampled
  configurations. We introduce a novel algorithm, Hyperband, for this framework and
  analyze its theoretical properties, providing several desirable guarantees. Furthermore,
  we compare Hyperband with popular Bayesian optimization methods on a suite of hyperparameter
  optimization problems. We observe that Hyperband can provide over an order-of-magnitude
  speedup over our competitor set on a variety of deep-learning and kernel-based learning
  problems.
tags:
- deep learning
- hyperparameter optimization
- infinite-armed bandits
- model selection
- online optimization
---
