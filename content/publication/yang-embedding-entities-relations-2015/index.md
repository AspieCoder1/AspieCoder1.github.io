---
title: Embedding Entities and Relations for Learning and Inference in Knowledge Bases
authors:
- Bishan Yang
- Wen-tau Yih
- Xiaodong He
- Jianfeng Gao
- Li Deng
date: '2015-08-29'
publishDate: '2024-09-13T09:52:59.603680Z'
publication_types:
- manuscript
abstract: We consider learning representations of entities and relations in KBs using
  the neural-embedding approach. We show that most existing models, including NTN
  (Socher et al., 2013) and TransE (Bordes et al., 2013b), can be generalized under
  a unified learning framework, where entities are low-dimensional vectors learned
  from a neural network and relations are bilinear and/or linear mapping functions.
  Under this framework, we compare a variety of embedding models on the link prediction
  task. We show that a simple bilinear formulation achieves new state-of-the-art results
  for the task (achieving a top-10 accuracy of 73.2% vs. 54.7% by TransE on Freebase).
  Furthermore, we introduce a novel approach that utilizes the learned relation embeddings
  to mine logical rules such as \"BornInCity(a,b) and CityInCountry(b,c) =$>$ Nationality(a,c)\".
  We find that embeddings learned from the bilinear objective are particularly good
  at capturing relational semantics and that the composition of relations is characterized
  by matrix multiplication. More interestingly, we demonstrate that our embedding-based
  rule extraction approach successfully outperforms a state-of-the-art confidence-based
  rule mining approach in mining Horn rules that involve compositional reasoning.
tags:
- Computer Science - Computation and Language
links:
- name: URL
  url: http://arxiv.org/abs/1412.6575
---
