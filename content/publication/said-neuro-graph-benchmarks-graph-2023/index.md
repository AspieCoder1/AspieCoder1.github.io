---
title: 'NeuroGraph: Benchmarks for Graph Machine Learning in Brain Connectomics'
authors:
- Anwar Said
- Roza G. Bayrak
- Tyler Derr
- Mudassir Shabbir
- Daniel Moyer
- Catie Chang
- Xenofon Koutsoukos
date: '2023-11-21'
publishDate: '2024-09-13T09:52:59.158056Z'
publication_types:
- manuscript
abstract: Machine learning provides a valuable tool for analyzing high-dimensional
  functional neuroimaging data, and is proving effective in predicting various neurological
  conditions, psychiatric disorders, and cognitive patterns. In functional magnetic
  resonance imaging (MRI) research, interactions between brain regions are commonly
  modeled using graph-based representations. The potency of graph machine learning
  methods has been established across myriad domains, marking a transformative step
  in data interpretation and predictive modeling. Yet, despite their promise, the
  transposition of these techniques to the neuroimaging domain has been challenging
  due to the expansive number of potential preprocessing pipelines and the large parameter
  search space for graph-based dataset construction. In this paper, we introduce NeuroGraph,
  a collection of graph-based neuroimaging datasets, and demonstrated its utility
  for predicting multiple categories of behavioral and cognitive traits. We delve
  deeply into the dataset generation search space by crafting 35 datasets that encompass
  static and dynamic brain connectivity, running in excess of 15 baseline methods
  for benchmarking. Additionally, we provide generic frameworks for learning on both
  static and dynamic graphs. Our extensive experiments lead to several key observations.
  Notably, using correlation vectors as node features, incorporating larger number
  of regions of interest, and employing sparser graphs lead to improved performance.
  To foster further advancements in graph-based data driven neuroimaging analysis,
  we offer a comprehensive open-source Python package that includes the benchmark
  datasets, baseline implementations, model training, and standard evaluation.
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Machine Learning
- Quantitative Biology - Neurons and Cognition
links:
- name: URL
  url: http://arxiv.org/abs/2306.06202
---