---
title: Open Vocabulary Learning on Source Code with a Graph-Structured Cache
authors:
- Milan Cvitkovic
- Badal Singh
- Anima Anandkumar
date: '2019-05-19'
publishDate: '2024-09-13T09:52:58.028622Z'
publication_types:
- manuscript
abstract: Machine learning models that take computer program source code as input
  typically use Natural Language Processing (NLP) techniques. However, a major challenge
  is that code is written using an open, rapidly changing vocabulary due to, e.g.,
  the coinage of new variable and method names. Reasoning over such a vocabulary is
  not something for which most NLP methods are designed. We introduce a Graph-Structured
  Cache to address this problem; this cache contains a node for each new word the
  model encounters with edges connecting each word to its occurrences in the code.
  We find that combining this graph-structured cache strategy with recent Graph-Neural-Network-based
  models for supervised learning on code improves the models' performance on a code
  completion task and a variable naming task --- with over $100%$ relative improvement
  on the latter --- at the cost of a moderate increase in computation time.
tags:
- Computer Science - Machine Learning
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/1810.08305
---
