---
title: Auto-Encoding Variational Bayes
authors:
- Diederik P. Kingma
- Max Welling
date: '2013-12-23'
publishDate: '2024-09-13T09:52:58.681340Z'
publication_types:
- paper-conference
abstract: Can we efficiently learn the parameters of directed probabilistic models,
  in the presence of continuous latent variables with intractable posterior distributions?
  We introduce an unsupervised on-line learning method that efficiently optimizes
  the variational lower bound on the marginal likelihood and that, under some mild
  conditions, even works in the intractable case. The method optimizes a probabilistic
  encoder (also called a recognition network) to approximate the intractable posterior
  distribution of the latent variables. The crucial element is a reparameterization
  of the variational bound with an independent noise variable, yielding a stochastic
  objective function which can be jointly optimized w.r.t. variational and generative
  parameters using standard gradient-based stochastic optimization methods. Theoretical
  advantages are reflected in experimental results.
links:
- name: URL
  url: https://openreview.net/forum?id=33X9fd2-9FyZd
---
