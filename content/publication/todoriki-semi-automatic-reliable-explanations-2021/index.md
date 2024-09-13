---
title: Semi-Automatic Reliable Explanations for Prediction in Graphs
authors:
- Masaru Todoriki
- Masafumi Shingu
- Shotaro Yano
- Arseny Tolmachev
- Tao Komikado
- Koji Maruhashi
date: '2021-01-01'
publishDate: '2024-09-13T09:52:59.369586Z'
publication_types:
- paper-conference
publication: '*2021 IEEE 11th Annual Computing and Communication Workshop and Conference
  (CCWC)*'
abstract: 'We discuss reliability for local explanations for prediction in graphs.
  Meaningfully explaining predictions of machine learning models is an open and important
  research question particularly in relation to human judgement. Objectively evaluating
  explanation is strongly required to make Artificial Intelligence trusted. Model-agnostic
  local explanation methods such as LIME have recently emerged and are being widely
  used for commonly used types of data: tables, texts, and images. A locally linear
  regression model is constructed using perturbed data generated in the vicinity of
  the instance to be explained with LIME. However, the creation of adequate perturbed
  data is not necessarily easy depending on the task and dataset leading to less explainability
  and instability of explanations. It is more problematic to apply such local explanation
  methods to graph data because there are difficulties unique to graphs such as the
  complexity of the structure and the variety of definitions of the distance among
  them. We propose a local explanation method for graphs originated from LIME and
  for fundamental synthetic datasets experimentally investigate the characteristics
  of perturbed data concerning explainability, e.g., “what perturbed data can increase
  explainability?” or “is there a criterion to determine reliable explanations regarding
  perturbed data?”. The effect of the following various factors in the explanation
  process are investigated: a generation method for perturbed data, distance function,
  dataset, prediction model, and data augmentation due to noise in training. Although
  the effect of these factors is quite complex, the ratio of the perturbed data that
  has a different class than the instance has is the most important index for higher
  explanations independently of the complex effect. We also propose a practical method
  to semi-automatically determine a reliable explanation with minimum human support
  using this index. We also evaluate a model-agnostic manner in our proposed method
  for graph classification tasks and prediction models such as graph convolutional
  networks (GCNs) or support vector machines (SVM) with graph kernels. The results
  indicate that the locally linear regression model can work well under specific situations.
  Moreover, the possibility to obtain better explainability than with the state-of-the-art
  graph explanation method GNNExplainer is shown as a reference.'
tags:
- Data models
- Explainable Artificial Intelligence
- Graph
- Indexes
- Interpretability
- Linear regression
- Local Explanation
- Machine Learning
- Model-Agnostic
- Predictive models
- Reliability
- Support vector machines
- Task analysis
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/9375922
---
