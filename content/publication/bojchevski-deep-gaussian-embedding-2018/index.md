---
title: 'Deep Gaussian Embedding of Graphs: Unsupervised Inductive Learning via Ranking'
authors:
- Aleksandar Bojchevski
- Stephan Günnemann
date: '2018-02-15'
publishDate: '2024-09-13T09:52:57.850041Z'
publication_types:
- paper-conference
abstract: 'Methods that learn representations of nodes in a graph play a critical
  role in network analysis since they enable many downstream learning tasks. We propose
  Graph2Gauss - an approach that can efficiently learn versatile node embeddings on
  large scale (attributed) graphs that show strong performance on tasks such as link
  prediction and node classification. Unlike most approaches that represent nodes
  as point vectors in a low-dimensional continuous space, we embed each node as a
  Gaussian distribution, allowing us to capture uncertainty about the representation.
  Furthermore, we propose an unsupervised method that handles inductive learning scenarios
  and is applicable to different types of graphs: plain/attributed, directed/undirected.
  By leveraging both the network structure and the associated node attributes, we
  are able to generalize to unseen nodes without additional training. To learn the
  embeddings we adopt a personalized ranking formulation w.r.t. the node distances
  that exploits the natural ordering of the nodes imposed by the network structure.
  Experiments on real world networks demonstrate the high performance of our approach,
  outperforming state-of-the-art network embedding methods on several different tasks.
  Additionally, we demonstrate the benefits of modeling uncertainty - by analyzing
  it we can estimate neighborhood diversity and detect the intrinsic latent dimensionality
  of a graph.'
links:
- name: URL
  url: https://openreview.net/forum?id=r1ZdKJ-0W
---