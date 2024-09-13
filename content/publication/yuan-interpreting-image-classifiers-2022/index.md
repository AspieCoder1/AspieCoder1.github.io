---
title: Interpreting Image Classifiers by Generating Discrete Masks
authors:
- Hao Yuan
- Lei Cai
- Xia Hu
- Jie Wang
- Shuiwang Ji
date: '2022-04-01'
publishDate: '2024-09-13T09:52:59.661725Z'
publication_types:
- article-journal
publication: '*IEEE Computer Society*'
abstract: Deep models are commonly treated as black-boxes and lack interpretability.
  Here, we propose a novel approach to interpret deep image classifiers by generating
  discrete masks. Our method follows the generative adversarial network formalism.
  The deep model to be interpreted is the discriminator while we train a generator
  to explain it. The generator is trained to capture discriminative image regions
  that should convey the same or similar meaning as the original image from the model’s
  perspective. It produces a probability map from which a discrete mask can be sampled.
  Then the discriminator is used to measure the quality of the sampled mask and provide
  feedbacks for updating. Due to the sampling operations, the generator cannot be
  trained directly by back-propagation. We propose to update it using policy gradient.
  Furthermore, we propose to incorporate gradients as auxiliary information to reduce
  the search space and facilitate training. We conduct both quantitative and qualitative
  experiments on the ILSVRC dataset. Experimental results indicate that our method
  can provide reasonable explanations for predictions and outperform existing approaches.
  In addition, our method can pass the model randomization test, indicating that it
  is reasoning the attribution of network predictions.
links:
- name: URL
  url: https://www.computer.org/csdl/journal/tp/2022/04/09214476/1nHNEVsfYTm
---
