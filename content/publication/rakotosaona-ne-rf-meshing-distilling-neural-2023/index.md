---
title: 'NeRFMeshing: Distilling Neural Radiance Fields into Geometrically-Accurate
  3D Meshes'
authors:
- Marie-Julie Rakotosaona
- Fabian Manhardt
- Diego Martin Arroyo
- Michael Niemeyer
- Abhijit Kundu
- Federico Tombari
date: '2023-03-16'
publishDate: '2024-09-13T09:52:59.055173Z'
publication_types:
- manuscript
abstract: With the introduction of Neural Radiance Fields (NeRFs), novel view synthesis
  has recently made a big leap forward. At the core, NeRF proposes that each 3D point
  can emit radiance, allowing to conduct view synthesis using differentiable volumetric
  rendering. While neural radiance fields can accurately represent 3D scenes for computing
  the image rendering, 3D meshes are still the main scene representation supported
  by most computer graphics and simulation pipelines, enabling tasks such as real
  time rendering and physics-based simulations. Obtaining 3D meshes from neural radiance
  fields still remains an open challenge since NeRFs are optimized for view synthesis,
  not enforcing an accurate underlying geometry on the radiance field. We thus propose
  a novel compact and flexible architecture that enables easy 3D surface reconstruction
  from any NeRF-driven approach. Upon having trained the radiance field, we distill
  the volumetric 3D representation into a Signed Surface Approximation Network, allowing
  easy extraction of the 3D mesh and appearance. Our final 3D mesh is physically accurate
  and can be rendered in real time on an array of devices.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2303.09431
---
