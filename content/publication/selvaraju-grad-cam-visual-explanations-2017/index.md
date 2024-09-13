---
title: 'Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization'
authors:
- Ramprasaath R. Selvaraju
- Michael Cogswell
- Abhishek Das
- Ramakrishna Vedantam
- Devi Parikh
- Dhruv Batra
date: '2017-10-01'
publishDate: '2024-09-13T09:52:59.220369Z'
publication_types:
- paper-conference
publication: '*2017 IEEE International Conference on Computer Vision (ICCV)*'
abstract: "We propose a technique for producing `visual explanations' for decisions
  from a large class of Convolutional Neural Network (CNN)-based models, making them
  more transparent. Our approach - Gradient-weighted Class Activation Mapping (Grad-CAM),
  uses the gradients of any target concept (say logits for `dog' or even a caption),
  flowing into the final convolutional layer to produce a coarse localization map
  highlighting the important regions in the image for predicting the concept. Unlike
  previous approaches, Grad- CAM is applicable to a wide variety of CNN model-families:
  (1) CNNs with fully-connected layers (e.g. VGG), (2) CNNs used for structured outputs
  (e.g. captioning), (3) CNNs used in tasks with multi-modal inputs (e.g. visual question
  answering) or reinforcement learning, without architectural changes or re-training.
  We combine Grad-CAM with existing fine-grained visualizations to create a high-resolution
  class-discriminative visualization, Guided Grad-CAM, and apply it to image classification,
  image captioning, and visual question answering (VQA) models, including ResNet-based
  architectures. In the context of image classification models, our visualizations
  (a) lend insights into failure modes of these models (showing that seemingly unreasonable
  predictions have reasonable explanations), (b) outperform previous methods on the
  ILSVRC-15 weakly-supervised localization task, (c) are more faithful to the underlying
  model, and (d) help achieve model generalization by identifying dataset bias. For
  image captioning and VQA, our visualizations show even non-attention based models
  can localize inputs. Finally, we design and conduct human studies to measure if
  Grad-CAM explanations help users establish appropriate trust in predictions from
  deep networks and show that Grad-CAM helps untrained users successfully discern
  a `stronger' deep network from a `weaker' one even when both make identical predictions.
  Our code is available at https: //github.com/ramprs/grad-cam/ along with a demo
  on CloudCV [2] and video at youtu.be/COjUB9Izk6E."
tags:
- Cats
- Computer architecture
- Dogs
- Knowledge discovery
- Visualization
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/8237336
---