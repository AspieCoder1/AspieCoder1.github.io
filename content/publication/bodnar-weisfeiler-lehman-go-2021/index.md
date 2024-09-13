---
title: 'Weisfeiler and Lehman Go Cellular: CW Networks'
authors:
- Cristian Bodnar
- Fabrizio Frasca
- Nina Otter
- Yuguang Wang
- Pietro Liò
- Guido F Montufar
- Michael Bronstein
date: '2021-01-01'
publishDate: '2024-09-13T09:52:57.842646Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems*'
abstract: Graph Neural Networks (GNNs) are limited in their expressive power, struggle
  with long-range interactions and lack a principled way to model higher-order structures.
  These problems can be attributed to the strong coupling between the computational
  graph and the input graph structure. The recently proposed Message Passing Simplicial
  Networks naturally decouple these elements by performing message passing on the
  clique complex of the graph. Nevertheless, these models can be severely constrained
  by the rigid combinatorial structure of Simplicial Complexes (SCs). In this work,
  we extend recent theoretical results on SCs to regular Cell Complexes, topological
  objects that flexibly subsume SCs and graphs. We show that this generalisation provides
  a powerful set of graph \"lifting\" transformations, each leading to a unique hierarchical
  message passing procedure. The resulting methods, which we collectively call CW
  Networks (CWNs), are strictly more powerful than the WL test and not less powerful
  than the 3-WL test. In particular, we demonstrate the effectiveness of one such
  scheme, based on rings, when applied to molecular graph problems. The proposed architecture
  benefits from provably larger expressivity than commonly used GNNs, principled modelling
  of higher-order signals and from compressing the distances between nodes. We demonstrate
  that our model achieves state-of-the-art results on a variety of molecular datasets.
links:
- name: URL
  url: 
    https://proceedings.neurips.cc/paper/2021/hash/157792e4abb490f99dbd738483e0d2d4-Abstract.html
---