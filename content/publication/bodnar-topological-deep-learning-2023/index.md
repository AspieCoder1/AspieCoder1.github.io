---
title: 'Topological Deep Learning: Graphs, Complexes, Sheaves'
authors:
- Cristian Bodnar
date: '2023-06-20T12:04:30Z'
publishDate: '2024-09-13T09:52:57.834234Z'
publication_types:
- thesis
abstract: The types of spaces where data resides - graphs, meshes, grids, manifolds
  - are becoming increasingly varied and heterogeneous. Therefore, translating ideas,
  models, and theoretical results between different domains is becoming more and more
  challenging. Nonetheless, two fundamental principles unite all these settings. The
  first states that data is localised, meaning that data is associated with some regions
  of the underlying space. The second says that data is relational, and this relational
  structure reflects how the various regions of the space overlap. It is natural to
  formalise these axioms using algebraic topology. The \"space'' in question is a
  topological space - a set with a neighbourhood structure - and the data attached
  to its neighbourhoods are algebraic objects like vector spaces. Since graphs, manifolds
  and everything in between is a topological space, we adopt this mathematical viewpoint
  to smoothly transition between domains, improve our theoretical understanding of
  existent models and design new ones, including for spaces that are yet to be explored
  in Machine Learning. Guided by this perspective, this work introduces Topological
  Deep Learning, a research programme studying (deep) models performing inference
  on data glued to a topological space. This thesis includes four research works expanding
  upon the directions outlined above. The first work proposes Message Passing Simplicial
  Networks (MPSNs), a family of models operating on simplicial complexes, a higher-dimensional
  generalisation of graphs coming from algebraic topology. We study the symmetries
  these models must satisfy, the topological invariants that describe their behaviour,
  and how they can learn representations based on discrete differential forms. The
  second work takes this generalisation further to cell complexes, a class of spaces
  that also subsume simplicial complexes. We show their additional flexibility benefits
  molecular applications, where the resulting models outperform prior art on molecular
  property prediction tasks. The third work proposes a general topological framework
  for constructing graph coarsening (aka pooling) operators in a way that naturally
  generalises existing pooling approaches in computer vision. We show that this framework
  can be used to construct graph-based hierarchical models and visualise attributed
  graphs. Finally, the last work introduces a new perspective on graph models based
  on sheaf theory, a subfield of algebraic topology. Sheaves, which are mathematical
  data structures that naturally store the data attached to a topological space and
  its relational structure, faithfully realise the axiomatic principles of Topological
  Deep Learning. We show that sheaf structures on graphs are intimately connected
  with the asymptotic behaviour of message passing graph models and exploit these
  connections to design new sheaf-based convolutional architectures. We demonstrate
  that these models can cope with the challenges of oversmoothing and heterophilic
  graphs, which affect many existent graph models. Overall, this thesis introduces
  a novel topological perspective on deep learning for structured data, whose ramifications
  establish many new connections with algebraic topology.
links:
- name: URL
  url: https://www.repository.cam.ac.uk/handle/1810/350982
---
