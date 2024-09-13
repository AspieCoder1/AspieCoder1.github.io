---
title: 'R2L: Distilling Neural Radiance Field to~Neural Light Field for~Efficient
  Novel View Synthesis'
authors:
- Huan Wang
- Jian Ren
- Zeng Huang
- Kyle Olszewski
- Menglei Chai
- Yun Fu
- Sergey Tulyakov
date: '2022-01-01'
publishDate: '2024-09-13T09:52:59.498916Z'
publication_types:
- paper-conference
publication: '*Springer Nature Switzerland*'
abstract: 'Recent research explosion on Neural Radiance Field (NeRF) shows the encouraging
  potential to represent complex scenes with neural networks. One major drawback of
  NeRF is its prohibitive inference time: Rendering a single pixel requires querying
  the NeRF network hundreds of times. To resolve it, existing efforts mainly attempt
  to reduce the number of required sampled points. However, the problem of iterative
  sampling still exists. On the other hand, Neural Light Field (NeLF) presents a more
  straightforward representation over NeRF in novel view synthesis – the rendering
  of a pixel amounts to one single forward pass without ray-marching. In this work,
  we present a deep residual MLP network (88 layers) to effectively learn the light
  field. We show the key to successfully learning such a deep NeLF network is to have
  sufficient data, for which we transfer the knowledge from a pre-trained NeRF model
  via data distillation. Extensive experiments on both synthetic and real-world scenes
  show the merits of our method over other counterpart algorithms. On the synthetic
  scenes, we achieve $$26 sim 35 times $$26∼35×FLOPs reduction (per camera ray) and
  $$28 sim 31 times $$28∼31×runtime speedup, meanwhile delivering significantly better
  ($$1.4 sim 2.8$$1.4∼2.8dB average PSNR improvement) rendering quality than NeRF
  without any customized parallelism requirement.'
---
