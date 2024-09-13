---
title: 'ReGVD: revisiting graph neural networks for vulnerability detection'
authors:
- Van-Anh Nguyen
- Dai Quoc Nguyen
- Van Nguyen
- Trung Le
- Quan Hung Tran
- Dinh Phung
date: '2022-10-19'
publishDate: '2024-09-13T09:52:58.955707Z'
publication_types:
- paper-conference
publication: '*Proceedings of the ACM/IEEE 44th International Conference on Software
  Engineering: Companion Proceedings*'
abstract: 'Identifying vulnerabilities in the source code is essential to protect
  the software systems from cyber security attacks. It, however, is also a challenging
  step that requires specialized expertise in security and code representation. To
  this end, we aim to develop a general, practical, and programming language-independent
  model capable of running on various source codes and libraries without difficulty.
  Therefore, we consider vulnerability detection as an inductive text classification
  problem and propose ReGVD, a simple yet effective graph neural network-based model
  for the problem. In particular, ReGVD views each raw source code as a flat sequence
  of tokens to build a graph, wherein node features are initialized by only the token
  embedding layer of a pre-trained programming language (PL) model. ReGVD then leverages
  residual connection among GNN layers and examines a mixture of graph-level sum and
  max poolings to return a graph embedding for the source code. ReGVD outperforms
  the existing state-of-the-art models and obtains the highest accuracy on the real-world
  benchmark dataset from CodeXGLUE for vulnerability detection. Our code is available
  at: https://github.com/daiquocnguyen/GNN-ReGVD.'
tags:
- graph neural networks
- security
- text classification
- vulnerability detection
links:
- name: URL
  url: https://doi.org/10.1145/3510454.3516865
---
