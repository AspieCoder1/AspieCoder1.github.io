---
title: Colorful Image Colorization
authors:
- Richard Zhang
- Phillip Isola
- Alexei A. Efros
date: '2016-01-01'
publishDate: '2024-09-13T09:52:59.718984Z'
publication_types:
- paper-conference
publication: '*Computer Vision – ECCV 2016*'
abstract: Given a grayscale photograph as input, this paper attacks the problem of
  hallucinating a plausible color version of the photograph. This problem is clearly
  underconstrained, so previous approaches have either relied on significant user
  interaction or resulted in desaturated colorizations. We propose a fully automatic
  approach that produces vibrant and realistic colorizations. We embrace the underlying
  uncertainty of the problem by posing it as a classification task and use class-rebalancing
  at training time to increase the diversity of colors in the result. The system is
  implemented as a feed-forward pass in a CNN at test time and is trained on over
  a million color images. We evaluate our algorithm using a “colorization Turing test,”
  asking human participants to choose between a generated and ground truth color image.
  Our method successfully fools humans on 32~% of the trials, significantly higher
  than previous methods. Moreover, we show that colorization can be a powerful pretext
  task for self-supervised feature learning, acting as a cross-channel encoder. This
  approach results in state-of-the-art performance on several feature learning benchmarks.
tags:
- CNNs
- Colorization
- Self-supervised learning
- Vision for graphics
---