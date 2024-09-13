---
title: MCI Identification by Joint Learning on Multiple MRI Data
authors:
- Yue Gao
- Chong-Yaw Wee
- Minjeong Kim
- Panteleimon Giannakopoulos
- Marie-Louise Montandon
- Sven Haller
- Dinggang Shen
date: '2015-10-01'
publishDate: '2024-09-13T09:52:58.261704Z'
publication_types:
- article-journal
abstract: The identification of subtle brain changes that are associated with mild
  cognitive impairment (MCI), the at-risk stage of Alzheimer’s disease, is still a
  challenging task. Different from existing works, which employ multimodal data (e.g.,
  MRI, PET or CSF) to identify MCI subjects from normal elderly controls, we use four
  MRI sequences, including T1-weighted MRI (T1), Diffusion Tensor Imaging (DTI), Resting-State
  functional MRI (RS-fMRI) and Arterial Spin Labeling (ASL) perfusion imaging. Since
  these MRI sequences simultaneously capture various aspects of brain structure and
  function during clinical routine scan, it simplifies finding the relationship between
  subjects by incorporating the mutual information among them. To this end, we devise
  a hypergraph-based semi-supervised learning algorithm. In particular, we first construct
  a hypergraph for each of MRI sequences separately using a star expansion method
  with both the training and testing data. A centralized learning is then performed
  to model the optimal relevance between subjects by incorporating mutual information
  between different MRI sequences. We then combine all centralized hypergraphs by
  learning the optimal weight of each hypergraph based on the minimum Laplacian. We
  apply our proposed method on a cohort of 41 consecutive MCI subjects and 63 age-and-gender
  matched controls with four MRI sequences. Our method achieves at least a 7.61% improvement
  in classification accuracy compared to state-of-the-art methods using multiple MRI
  data.
links:
- name: URL
  url: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4773025/
---
