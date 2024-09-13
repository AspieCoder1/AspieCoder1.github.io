---
title: Towards Foundation Models for Knowledge Graph Reasoning
authors:
- Mikhail Galkin
- Xinyu Yuan
- Hesham Mostafa
- Jian Tang
- Zhaocheng Zhu
date: '2023-10-06'
publishDate: '2024-09-13T09:52:58.240548Z'
publication_types:
- manuscript
abstract: Foundation models in language and vision have the ability to run inference
  on any textual and visual inputs thanks to the transferable representations such
  as a vocabulary of tokens in language. Knowledge graphs (KGs) have different entity
  and relation vocabularies that generally do not overlap. The key challenge of designing
  foundation models on KGs is to learn such transferable representations that enable
  inference on any graph with arbitrary entity and relation vocabularies. In this
  work, we make a step towards such foundation models and present ULTRA, an approach
  for learning universal and transferable graph representations. ULTRA builds relational
  representations as a function conditioned on their interactions. Such a conditioning
  strategy allows a pre-trained ULTRA model to inductively generalize to any unseen
  KG with any relation vocabulary and to be fine-tuned on any graph. Conducting link
  prediction experiments on 57 different KGs, we find that the zero-shot inductive
  inference performance of a single pre-trained ULTRA model on unseen graphs of various
  sizes is often on par or better than strong baselines trained on specific graphs.
  Fine-tuning further boosts the performance.
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Computation and Language
links:
- name: URL
  url: http://arxiv.org/abs/2310.04562
---
