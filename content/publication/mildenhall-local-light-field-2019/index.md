---
title: 'Local Light Field Fusion: Practical View Synthesis with Prescriptive Sampling
  Guidelines'
authors:
- Ben Mildenhall
- Pratul P. Srinivasan
- Rodrigo Ortiz-Cayon
- Nima Khademi Kalantari
- Ravi Ramamoorthi
- Ren Ng
- Abhishek Kar
date: '2019-05-02'
publishDate: '2024-09-13T09:52:58.927185Z'
publication_types:
- manuscript
abstract: We present a practical and robust deep learning solution for capturing and
  rendering novel views of complex real world scenes for virtual exploration. Previous
  approaches either require intractably dense view sampling or provide little to no
  guidance for how users should sample views of a scene to reliably render high-quality
  novel views. Instead, we propose an algorithm for view synthesis from an irregular
  grid of sampled views that first expands each sampled view into a local light field
  via a multiplane image (MPI) scene representation, then renders novel views by blending
  adjacent local light fields. We extend traditional plenoptic sampling theory to
  derive a bound that specifies precisely how densely users should sample views of
  a given scene when using our algorithm. In practice, we apply this bound to capture
  and render views of real world scenes that achieve the perceptual quality of Nyquist
  rate view sampling while using up to 4000x fewer views. We demonstrate our approach's
  practicality with an augmented reality smartphone app that guides users to capture
  input images of a scene and viewers that enable realtime virtual exploration on
  desktop and mobile platforms.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Graphics
links:
- name: URL
  url: http://arxiv.org/abs/1905.00889
---
