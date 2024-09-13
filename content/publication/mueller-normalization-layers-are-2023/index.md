---
title: Normalization Layers Are All That Sharpness-Aware Minimization Needs
authors:
- Maximilian Mueller
- Tiffany Vlaar
- David Rolnick
- Matthias Hein
date: '2023-11-17'
publishDate: '2024-09-13T09:52:58.948865Z'
publication_types:
- manuscript
abstract: Sharpness-aware minimization (SAM) was proposed to reduce sharpness of minima
  and has been shown to enhance generalization performance in various settings. In
  this work we show that perturbing only the affine normalization parameters (typically
  comprising 0.1% of the total parameters) in the adversarial step of SAM can outperform
  perturbing all of the parameters.This finding generalizes to different SAM variants
  and both ResNet (Batch Normalization) and Vision Transformer (Layer Normalization)
  architectures. We consider alternative sparse perturbation approaches and find that
  these do not achieve similar performance enhancement at such extreme sparsity levels,
  showing that this behaviour is unique to the normalization layers. Although our
  findings reaffirm the effectiveness of SAM in improving generalization performance,
  they cast doubt on whether this is solely caused by reduced sharpness.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2306.04226
---
