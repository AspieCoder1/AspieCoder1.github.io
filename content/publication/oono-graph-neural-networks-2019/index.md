---
title: Graph Neural Networks Exponentially Lose Expressive Power for Node Classification
authors:
- Kenta Oono
- Taiji Suzuki
date: '2019-09-23'
publishDate: '2024-09-13T09:52:58.975453Z'
publication_types:
- paper-conference
abstract: Graph Neural Networks (graph NNs) are a promising deep learning approach
  for analyzing graph-structured data. However, it is known that they do not improve
  (or sometimes worsen) their predictive performance as we pile up many layers and
  add non-lineality. To tackle this problem, we investigate the expressive power of
  graph NNs via their asymptotic behaviors as the layer size tends to infinity. Our
  strategy is to generalize the forward propagation of a Graph Convolutional Network
  (GCN), which is a popular graph NN variant, as a specific dynamical system. In the
  case of a GCN, we show that when its weights satisfy the conditions determined by
  the spectra of the (augmented) normalized Laplacian, its output exponentially approaches
  the set of signals that carry information of the connected components and node degrees
  only for distinguishing nodes. Our theory enables us to relate the expressive power
  of GCNs with the topological information of the underlying graphs inherent in the
  graph spectra. To demonstrate this, we characterize the asymptotic behavior of GCNs
  on the Erd Hos -- R 'enyi graph. We show that when the Erd Hos -- R 'enyi graph
  is sufficiently dense and large, a broad range of GCNs on it suffers from the ``information
  loss\" in the limit of infinite layers with high probability. Based on the theory,
  we provide a principled guideline for weight normalization of graph NNs. We experimentally
  confirm that the proposed weight scaling enhances the predictive performance of
  GCNs in real data. Code is available at https://github.com/delta2323/gnn-asymptotics.
links:
- name: URL
  url: https://openreview.net/forum?id=S1ldO2EFPr
---
