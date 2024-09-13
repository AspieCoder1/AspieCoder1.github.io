---
title: 'MultiSage: Empowering GCN with Contextualized Multi-Embeddings on Web-Scale
  Multipartite Networks'
authors:
- Carl Yang
- Aditya Pal
- Andrew Zhai
- Nikil Pancha
- Jiawei Han
- Charles Rosenberg
- Jure Leskovec
date: '2020-08-20'
publishDate: '2024-09-13T09:52:59.618422Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 26th ACM SIGKDD International Conference on Knowledge
  Discovery & Data Mining*'
abstract: Graph convolutional networks (GCNs) are a powerful class of graph neural
  networks. Trained in a semi-supervised end-to-end fashion, GCNs can learn to integrate
  node features and graph structures to generate high-quality embeddings that can
  be used for various downstream tasks like search and recommendation. However, existing
  GCNs mostly work on homogeneous graphs and consider a single embedding for each
  node, which do not sufficiently model the multi-facet nature and complex interaction
  of nodes in real-world networks. Here, we present a contextualized GCN engine by
  modeling the multipartite networks of target nodes and their intermediatecontext
  nodes that specify the contexts of their interactions. Towards the neighborhood
  aggregation process, we devise a contextual masking operation at the feature level
  and a contextual attention mechanism at the node level to achieve interaction contextualization
  by treating neighboring target nodes based on intermediate context nodes. Consequently,
  we compute multiple embeddings for target nodes that capture their diverse facets
  and different interactions during graph convolution, which is useful for fine-grained
  downstream applications. To enable efficient web-scale training, we build a parallel
  random walk engine to pre-sample contextualized neighbors, and a Hadoop2-based data
  provider pipeline to pre-join training data, dynamically reduce multi-GPU training
  time, and avoid high memory cost. Extensive experiments on the bipartite Pinterest
  graph and tripartite OAG graph corroborate the advantage of the proposed system.
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3394486.3403293
---