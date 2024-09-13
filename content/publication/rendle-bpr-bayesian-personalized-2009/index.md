---
title: 'BPR: Bayesian Personalized Ranking from Implicit Feedback'
authors:
- Steffen Rendle
- Christoph Freudenthaler
- Zeno Gantner
- Lars Schmidt-Thieme
date: '2009-01-01'
publishDate: '2024-09-13T09:52:59.095699Z'
publication_types:
- article-journal
abstract: 'Item recommendation is the task of predicting a personalized ranking on
  a set of items (e.g. websites, movies, products). In this paper, we investigate
  the most common scenario with implicit feedback (e.g. clicks, purchases). There
  are many methods for item recommendation from implicit feedback like matrix factorization
  (MF) or adaptive knearest-neighbor (kNN). Even though these methods are designed
  for the item prediction task of personalized ranking, none of them is directly optimized
  for ranking. In this paper we present a generic optimization criterion BPR-Opt for
  personalized ranking that is the maximum posterior estimator derived from a Bayesian
  analysis of the problem. We also provide a generic learning algorithm for optimizing
  models with respect to BPR-Opt. The learning method is based on stochastic gradient
  descent with bootstrap sampling. We show how to apply our method to two state-of-the-art
  recommender models: matrix factorization and adaptive kNN. Our experiments indicate
  that for the task of personalized ranking our optimization method outperforms the
  standard learning techniques for MF and kNN. The results show the importance of
  optimizing models for the right criterion.'
---