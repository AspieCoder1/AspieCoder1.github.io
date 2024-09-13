---
title: A Theory of Neural Tangent Kernel Alignment and Its Influence on Training
authors:
- Haozhe Shan
- Blake Bordelon
date: '2022-02-09'
publishDate: '2024-09-13T09:52:59.235018Z'
publication_types:
- manuscript
abstract: The training dynamics and generalization properties of neural networks (NN)
  can be precisely characterized in function space via the neural tangent kernel (NTK).
  Structural changes to the NTK during training reflect feature learning and underlie
  the superior performance of networks outside of the static kernel regime. In this
  work, we seek to theoretically understand kernel alignment, a prominent and ubiquitous
  structural change that aligns the NTK with the target function. We first study a
  toy model of kernel evolution in which the NTK evolves to accelerate training and
  show that alignment naturally emerges from this demand. We then study alignment
  mechanism in deep linear networks and two layer ReLU networks. These theories provide
  good qualitative descriptions of kernel alignment and specialization in practical
  networks and identify factors in network architecture and data structure that drive
  kernel alignment. In nonlinear networks with multiple outputs, we identify the phenomenon
  of kernel specialization, where the kernel function for each output head preferentially
  aligns to its own target function. Together, our results provide a mechanistic explanation
  of how kernel alignment emerges during NN training and a normative explanation of
  how it benefits training.
tags:
- Computer Science - Machine Learning
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2105.14301
---
