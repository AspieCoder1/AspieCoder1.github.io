---
title: Combining Label Propagation and Simple Models Out-performs Graph Neural Networks
authors:
- Qian Huang
- Horace He
- Abhay Singh
- Ser-Nam Lim
- Austin R. Benson
date: '2020-11-02'
publishDate: '2024-09-13T09:52:58.529946Z'
publication_types:
- manuscript
abstract: 'Graph Neural Networks (GNNs) are the predominant technique for learning
  over graphs. However, there is relatively little understanding of why GNNs are successful
  in practice and whether they are necessary for good performance. Here, we show that
  for many standard transductive node classification benchmarks, we can exceed or
  match the performance of state-of-the-art GNNs by combining shallow models that
  ignore the graph structure with two simple post-processing steps that exploit correlation
  in the label structure: (i) an \"error correlation\" that spreads residual errors
  in training data to correct errors in test data and (ii) a \"prediction correlation\"
  that smooths the predictions on the test data. We call this overall procedure Correct
  and Smooth (C&S), and the post-processing steps are implemented via simple modifications
  to standard label propagation techniques from early graph-based semi-supervised
  learning methods. Our approach exceeds or nearly matches the performance of state-of-the-art
  GNNs on a wide variety of benchmarks, with just a small fraction of the parameters
  and orders of magnitude faster runtime. For instance, we exceed the best known GNN
  performance on the OGB-Products dataset with 137 times fewer parameters and greater
  than 100 times less training time. The performance of our methods highlights how
  directly incorporating label information into the learning algorithm (as was done
  in traditional techniques) yields easy and substantial performance gains. We can
  also incorporate our techniques into big GNN models, providing modest gains. Our
  code for the OGB results is at https://github.com/Chillee/CorrectAndSmooth.'
tags:
- Computer Science - Machine Learning
- Computer Science - Social and Information Networks
links:
- name: URL
  url: http://arxiv.org/abs/2010.13993
---
