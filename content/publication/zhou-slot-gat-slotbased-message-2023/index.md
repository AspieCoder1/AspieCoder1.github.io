---
title: 'SlotGAT: Slot-based Message Passing for Heterogeneous Graphs'
authors:
- Ziang Zhou
- Jieming Shi
- Renchi Yang
- Yuanhang Zou
- Qing Li
date: '2023-07-03'
publishDate: '2024-09-13T09:52:59.797658Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 40th International Conference on Machine Learning*'
abstract: Heterogeneous graphs are ubiquitous to model complex data. There are urgent
  needs on powerful heterogeneous graph neural networks to effectively support important
  applications. We identify a potential semantic mixing issue in existing message
  passing processes, where the representations of the neighbors of a node v are forced
  to be transformed to the feature space of v for aggregation, though the neighbors
  are in different types. That is, the semantics in different node types are entangled
  together into node v’s representation. To address the issue, we propose SlotGAT
  with separate message passing processes in slots, one for each node type, to maintain
  the representations in their own node-type feature spaces. Moreover, in a slot-based
  message passing layer, we design an attention mechanism for effective slot-wise
  message aggregation. Further, we develop a slot attention technique after the last
  layer of SlotGAT, to learn the importance of different slots in downstream tasks.
  Our analysis indicates that the slots in SlotGAT can preserve different semantics
  in various feature spaces. The superiority of SlotGAT is evaluated against 13 baselines
  on 6 datasets for node classification and link prediction. Our code is at https://github.com/scottjiao/SlotGAT_ICML23/.
links:
- name: URL
  url: https://proceedings.mlr.press/v202/zhou23j.html
---