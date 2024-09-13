---
title: 'GMAN: A Graph Multi-Attention Network for Traffic Prediction'
authors:
- Chuanpan Zheng
- Xiaoliang Fan
- Cheng Wang
- Jianzhong Qi
date: '2020-04-03'
publishDate: '2024-09-13T09:52:59.775800Z'
publication_types:
- article-journal
abstract: Long-term traffic prediction is highly challenging due to the complexity
  of traffic systems and the constantly changing nature of many impacting factors.
  In this paper, we focus on the spatio-temporal factors, and propose a graph multi-attention
  network (GMAN) to predict traffic conditions for time steps ahead at different locations
  on a road network graph. GMAN adapts an encoder-decoder architecture, where both
  the encoder and the decoder consist of multiple spatio-temporal attention blocks
  to model the impact of the spatio-temporal factors on traffic conditions. The encoder
  encodes the input traffic features and the decoder predicts the output sequence.
  Between the encoder and the decoder, a transform attention layer is applied to convert
  the encoded traffic features to generate the sequence representations of future
  time steps as the input of the decoder. The transform attention mechanism models
  the direct relationships between historical and future time steps that helps to
  alleviate the error propagation problem among prediction time steps. Experimental
  results on two real-world traffic prediction tasks (i.e., traffic volume prediction
  and traffic speed prediction) demonstrate the superiority of GMAN. In particular,
  in the 1 hour ahead prediction, GMAN outperforms state-of-the-art methods by up
  to 4% improvement in MAE measure. The source code is available at https://github.com/zhengchuanpan/GMAN.
links:
- name: URL
  url: https://ojs.aaai.org/index.php/AAAI/article/view/5477
---