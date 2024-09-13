---
title: 'pixelNeRF: Neural Radiance Fields from One or Few Images'
authors:
- Alex Yu
- Vickie Ye
- Matthew Tancik
- Angjoo Kanazawa
date: '2021-06-01'
publishDate: '2024-09-13T09:52:59.691131Z'
publication_types:
- paper-conference
abstract: We propose pixelNeRF, a learning framework that predicts a continuous neural
  scene representation conditioned on one or few input images. The existing approach
  for constructing neural radiance fields [27] involves optimizing the representation
  to every scene independently, requiring many calibrated views and significant compute
  time. We take a step towards resolving these shortcomings by introducing an architecture
  that conditions a NeRF on image inputs in a fully convolutional manner. This allows
  the network to be trained across multiple scenes to learn a scene prior, enabling
  it to perform novel view synthesis in a feed-forward manner from a sparse set of
  views (as few as one). Leveraging the volume rendering approach of NeRF, our model
  can be trained directly from images with no explicit 3D supervision. We conduct
  extensive experiments on ShapeNet benchmarks for single image novel view synthesis
  tasks with held-out objects as well as entire unseen categories. We further demonstrate
  the flexibility of pixelNeRF by demonstrating it on multi-object ShapeNet scenes
  and real scenes from the DTU dataset. In all cases, pixelNeRF outperforms current
  state-of-the-art baselines for novel view synthesis and single image 3D reconstruction.
  For the video and code, please visit the project website:https://alexyu.net/pixelnerf.
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/9577688
---
