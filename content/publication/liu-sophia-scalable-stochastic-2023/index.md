---
title: 'Sophia: A Scalable Stochastic Second-order Optimizer for Language Model Pre-training'
authors:
- Hong Liu
- Zhiyuan Li
- David Hall
- Percy Liang
- Tengyu Ma
date: '2023-10-17'
publishDate: '2024-09-13T09:52:58.820682Z'
publication_types:
- manuscript
abstract: Given the massive cost of language model pre-training, a non-trivial improvement
  of the optimization algorithm would lead to a material reduction on the time and
  cost of training. Adam and its variants have been state-of-the-art for years, and
  more sophisticated second-order (Hessian-based) optimizers often incur too much
  per-step overhead. In this paper, we propose Sophia, Second-order Clipped Stochastic
  Optimization, a simple scalable second-order optimizer that uses a light-weight
  estimate of the diagonal Hessian as the pre-conditioner. The update is the moving
  average of the gradients divided by the moving average of the estimated Hessian,
  followed by element-wise clipping. The clipping controls the worst-case update size
  and tames the negative impact of non-convexity and rapid change of Hessian along
  the trajectory. Sophia only estimates the diagonal Hessian every handful of iterations,
  which has negligible average per-step time and memory overhead. On language modeling
  with GPT models of sizes ranging from 125M to 1.5B, Sophia achieves a 2x speed-up
  compared to Adam in the number of steps, total compute, and wall-clock time, achieving
  the same perplexity with 50% fewer steps, less total compute, and reduced wall-clock
  time. Theoretically, we show that Sophia, in a much simplified setting, adapts to
  the heterogeneous curvatures in different parameter dimensions, and thus has a run-time
  bound that does not depend on the condition number of the loss.
tags:
- Computer Science - Computation and Language
- Computer Science - Machine Learning
- Mathematics - Optimization and Control
links:
- name: URL
  url: http://arxiv.org/abs/2305.14342
---