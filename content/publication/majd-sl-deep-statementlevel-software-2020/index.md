---
title: 'SLDeep: Statement-level software defect prediction using deep-learning model
  on static code features'
authors:
- Amirabbas Majd
- Mojtaba Vahidi-Asl
- Alireza Khalilian
- Pooria Poorsarvi-Tehrani
- Hassan Haghighi
date: '2020-06-01'
publishDate: '2024-09-13T09:52:58.870942Z'
publication_types:
- article-journal
abstract: Software defect prediction (SDP) seeks to estimate fault-prone areas of
  the code to focus testing activities on more suspicious portions. Consequently,
  high-quality software is released with less time and effort. The current SDP techniques
  however work at coarse-grained units, such as a module or a class, putting some
  burden on the developers to locate the fault. To address this issue, we propose
  a new technique called as Statement-Level software defect prediction using Deep-learning
  model (SLDeep). The significance of SLDeep for intelligent and expert systems is
  that it demonstrates a novel use of deep-learning models to the solution of a practical
  problem faced by software developers. To reify our proposal, we defined a suite
  of 32 statement-level metrics, such as the number of binary and unary operators
  used in a statement. Then, we applied as learning model, long short-term memory
  (LSTM). We conducted experiments using 119,989 C/C++ programs within Code4Bench.
  The programs comprise 2,356,458 lines of code of which 292,064 lines are faulty.
  The benchmark comprises a diverse set of programs and versions, written by thousands
  of developers. Therefore, it tends to give a model that can be used for cross-project
  SDP. In the experiments, our trained model could successfully classify the unseen
  data (that is, fault-proneness of new statements) with average performance measures
  0.979, 0.570, and 0.702 in terms of recall, precision, and accuracy, respectively.
  These experimental results suggest that SLDeep is effective for statement-level
  SDP. The impact of this work is twofold. Working at statement-level further alleviates
  developer's burden in pinpointing the fault locations. Second, cross-project feature
  of SLDeep helps defect prediction research become more industrially-viable.
tags:
- Defect
- Fault prediction model
- Machine learning
- Software fault proneness
- Software metric
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0957417419308735
---
