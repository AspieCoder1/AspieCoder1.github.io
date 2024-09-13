---
title: 'Graph Neural Tangent Kernel: Fusing Graph Neural Networks with Graph Kernels'
authors:
- Simon S Du
- Kangcheng Hou
- Russ R Salakhutdinov
- Barnabas Poczos
- Ruosong Wang
- Keyulu Xu
date: '2019-01-01'
publishDate: '2024-09-13T09:52:58.130596Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems*'
abstract: While graph kernels (GKs) are easy to train and enjoy provable theoretical
  guarantees, their practical performances are limited by their expressive power,
  as the kernel function often depends on hand-crafted combinatorial features of graphs.
  Compared to graph kernels, graph neural networks (GNNs) usually achieve better practical
  performance, as GNNs use multi-layer architectures and non-linear activation functions
  to extract high-order information of graphs as features. However, due to the large
  number of hyper-parameters and the non-convex nature of the training procedure,
  GNNs are harder to train. Theoretical guarantees of GNNs are also not well-understood.
  Furthermore, the expressive power of GNNs scales with the number of parameters,
  and thus it is hard to exploit the full power of GNNs when computing resources are
  limited. The current paper presents a new class of graph kernels, Graph Neural Tangent
  Kernels (GNTKs), which correspond to  emphinfinitely wide multi-layer GNNs trained
  by gradient descent. GNTKs enjoy the full expressive power of GNNs and inherit advantages
  of GKs. Theoretically, we show GNTKs provably learn a class of smooth functions
  on graphs. Empirically, we test GNTKs on graph classification datasets and show
  they achieve strong performance.
links:
- name: URL
  url: 
    https://proceedings.neurips.cc/paper_files/paper/2019/hash/663fd3c5144fd10bd5ca6611a9a5b92d-Abstract.html
---
