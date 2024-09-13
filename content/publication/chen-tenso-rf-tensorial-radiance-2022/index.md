---
title: 'TensoRF: Tensorial Radiance Fields'
authors:
- Anpei Chen
- Zexiang Xu
- Andreas Geiger
- Jingyi Yu
- Hao Su
date: '2022-01-01'
publishDate: '2024-09-13T09:52:57.962389Z'
publication_types:
- paper-conference
abstract: We present TensoRF, a novel approach to model and reconstruct radiance fields.
  Unlike NeRF that purely uses MLPs, we model the radiance field of a scene as a 4D
  tensor, which represents a 3D voxel grid with per-voxel multi-channel features.  Our
  central idea is to factorize the 4D scene tensor into multiple compact low-rank
  tensor components. We demonstrate that applying traditional CANDECOMP/PARAFAC (CP)
  decomposition – that factorizes tensors into rank-one components with compact vectors
  – in our framework leads to improvements over vanilla NeRF. To further boost performance,
  we introduce a novel vector-matrix (VM) decomposition that relaxes the low-rank
  constraints for two modes of a tensor and factorizes tensors into compact vector
  and matrix factors. Beyond superior rendering quality, our models with CP and VM
  decompositions lead to a significantly lower memory footprint in comparison to previous
  and concurrent works that directly optimize per-voxel features. Experimentally,
  we demonstrate that TensoRF with CP decomposition achieves fast reconstruction ($$$<$30$$$<$30min)
  with better rendering quality and even a smaller model size ($$$<$4$$$<$4MB) compared
  to NeRF. Moreover, TensoRF with VM decomposition further boosts rendering quality
  and outperforms previous state-of-the-art methods, while reducing the reconstruction
  time ($$$<$10$$$<$10min) and retaining a compact model size ($$$<$75$$$<$75MB).
---
