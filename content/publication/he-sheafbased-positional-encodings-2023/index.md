---
title: Sheaf-based Positional Encodings for Graph Neural Networks
authors:
- Yu He
- Cristian Bodnar
- Pietro Lio
date: '2023-11-29'
publishDate: '2024-09-13T09:52:58.463568Z'
publication_types:
- paper-conference
abstract: Graph Neural Networks (GNNs) work directly with graph-structured data, capitalising
  on relational information among entities. One limitation of GNNs is their reliance
  on local interactions among connected nodes. GNNs may generate identical node embeddings
  for similar local neighbourhoods and fail to distinguish structurally distinct graphs.
  Positional encodings help to break the locality constraint by informing the nodes
  of their global positions in the graph. Furthermore, they are required by Graph
  Transformers to encode structural information. However, existing positional encodings
  based on the graph Laplacian only encode structural information and are typically
  fixed. To address these limitations, we propose a novel approach to design positional
  encodings using sheaf theory. The sheaf Laplacian can be learnt from node data,
  allowing it to encode both the structure and semantic information. We present two
  methodologies for creating sheaf-based positional encodings, showcasing their efficacy
  in node and graph tasks. Our work advances the integration of sheaves in graph learning,
  paving the way for innovative GNN techniques that draw inspiration from geometry
  and topology.
links:
- name: URL
  url: https://openreview.net/forum?id=ZtAabWUPu3
---
