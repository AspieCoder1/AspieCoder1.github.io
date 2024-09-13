---
title: 'RelEx: A Model-Agnostic Relational Model Explainer'
authors:
- Yue Zhang
- David Defazio
- Arti Ramesh
date: '2021-07-30'
publishDate: '2024-09-13T09:52:59.754127Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2021 AAAI/ACM Conference on AI, Ethics, and Society*'
abstract: In recent years, considerable progress has been made on improving the interpretability
  of machine learning models. This is essential, as complex deep learning models with
  millions of parameters produce state of the art performance, but it can be nearly
  impossible to explain their predictions. While various explainability techniques
  have achieved impressive results, nearly all of them assume each data instance to
  be independent and identically distributed (iid). This excludes relational models,
  such as Statistical Relational Learning (SRL), and the recently popular Graph Neural
  Networks (GNNs), resulting in few options to explain them. While there does exist
  work on explaining GNNs, GNN-Explainer, they assume access to the gradients of the
  model to learn explanations, which is restrictive in terms of its applicability
  across non-differentiable relational models and practicality. In this work, we develop
  RelEx, amodel-agnostic relational explainer to explain black-box relational models
  with only access to the outputs of the black-box. RelEx is able to explain any relational
  model, including SRL models and GNNs. We compare RelEx to the state-of-the-art relational
  explainer, GNN-Explainer, and relational extensions of iid explanation models and
  show that RelEx achieves comparable or better performance, while remaining model-agnostic.
tags:
- model-agnostic
- relational explainer
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3461702.3462562
---
