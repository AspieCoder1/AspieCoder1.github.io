---
title: Rethinking Sharpness-Aware Minimization as Variational Inference
authors:
- Szilvia Ujváry
- Zsigmond Telek
- Anna Kerekes
- Anna Mészáros
- Ferenc Huszár
date: '2022-10-19'
publishDate: '2024-09-13T09:52:59.413608Z'
publication_types:
- manuscript
abstract: Sharpness-aware minimization (SAM) aims to improve the generalisation of
  gradient-based learning by seeking out flat minima. In this work, we establish connections
  between SAM and Mean-Field Variational Inference (MFVI) of neural network parameters.
  We show that both these methods have interpretations as optimizing notions of flatness,
  and when using the reparametrisation trick, they both boil down to calculating the
  gradient at a perturbed version of the current mean parameter. This thinking motivates
  our study of algorithms that combine or interpolate between SAM and MFVI. We evaluate
  the proposed variational algorithms on several benchmark datasets, and compare their
  performance to variants of SAM. Taking a broader perspective, our work suggests
  that SAM-like updates can be used as a drop-in replacement for the reparametrisation
  trick.
tags:
- Computer Science - Machine Learning
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2210.10452
---
