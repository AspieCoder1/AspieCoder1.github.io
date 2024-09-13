---
title: Contrastive Representation Distillation
authors:
- Yonglong Tian
- Dilip Krishnan
- Phillip Isola
date: '2019-09-25'
publishDate: '2024-09-13T09:52:59.362773Z'
publication_types:
- paper-conference
abstract: Often we wish to transfer representational knowledge from one neural network
  to another. Examples include distilling a large network into a smaller one, transferring
  knowledge from one sensory modality to a second, or ensembling a collection of models
  into a single estimator. Knowledge distillation, the standard approach to these
  problems, minimizes the KL divergence between the probabilistic outputs of a teacher
  and student network. We demonstrate that this objective ignores important structural
  knowledge of the teacher network. This motivates an alternative objective by which
  we train a student to capture significantly more information in the teacher's representation
  of the data. We formulate this objective as contrastive learning. Experiments demonstrate
  that our resulting new objective outperforms knowledge distillation on a variety
  of knowledge transfer tasks, including single model compression, ensemble distillation,
  and cross-modal transfer. When combined with knowledge distillation, our method
  sets a state of the art in many transfer tasks, sometimes even outperforming the
  teacher network.
links:
- name: URL
  url: https://openreview.net/forum?id=SkgpBJrtvS
---