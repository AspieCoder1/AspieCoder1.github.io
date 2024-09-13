---
title: Two-Stream Adaptive Graph Convolutional Networks for Skeleton-Based Action
  Recognition
authors:
- L. Shi
- Y. Zhang
- J. Cheng
- H. Lu
date: -01-01
publishDate: '2024-09-13T09:52:58.729518Z'
publication_types:
- paper-conference
publication: '*2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition
  (CVPR)*'
abstract: In skeleton-based action recognition, graph convolutional networks (GCNs),
  which model the human body skeletons as spatiotemporal graphs, have achieved remarkable
  performance. However, in existing GCN-based methods, the topology of the graph is
  set manually, and it is fixed over all layers and input samples. This may not be
  optimal for the hierarchical GCN and diverse samples in action recognition tasks.
  In addition, the second-order information (the lengths and directions of bones)
  of the skeleton data, which is naturally more informative and discriminative for
  action recognition, is rarely investigated in existing methods. In this work, we
  propose a novel two-stream adaptive graph convolutional network (2s-AGCN) for skeleton-based
  action recognition. The topology of the graph in our model can be either uniformly
  or individually learned by the BP algorithm in an end-to-end manner. This data-driven
  method increases the flexibility of the model for graph construction and brings
  more generality to adapt to various data samples. Moreover, a two-stream framework
  is proposed to model both the first-order and the second-order information simultaneously,
  which shows notable improvement for the recognition accuracy. Extensive experiments
  on the two large-scale datasets, NTU-RGBD and Kinetics-Skeleton, demonstrate that
  the performance of our model exceeds the state-of-the-art with a significant margin.
tags:
- Action Recognition
- Deep Learning
links:
- name: URL
  url: http://doi.ieeecomputersociety.org/10.1109/CVPR.2019.01230
---
