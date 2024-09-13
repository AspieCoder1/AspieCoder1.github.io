---
title: Global Explainability of GNNs via Logic Combination of Learned Concepts
authors:
- Steve Azzolin
- Antonio Longa
- Pietro Barbiero
- Pietro Liò
- Andrea Passerini
date: '2023-04-11'
publishDate: '2024-09-13T09:52:57.712343Z'
publication_types:
- manuscript
abstract: While instance-level explanation of GNN is a well-studied problem with plenty
  of approaches being developed, providing a global explanation for the behaviour
  of a GNN is much less explored, despite its potential in interpretability and debugging.
  Existing solutions either simply list local explanations for a given class, or generate
  a synthetic prototypical graph with maximal score for a given class, completely
  missing any combinatorial aspect that the GNN could have learned. In this work,
  we propose GLGExplainer (Global Logic-based GNN Explainer), the first Global Explainer
  capable of generating explanations as arbitrary Boolean combinations of learned
  graphical concepts. GLGExplainer is a fully differentiable architecture that takes
  local explanations as inputs and combines them into a logic formula over graphical
  concepts, represented as clusters of local explanations. Contrary to existing solutions,
  GLGExplainer provides accurate and human-interpretable global explanations that
  are perfectly aligned with ground-truth explanations (on synthetic data) or match
  existing domain knowledge (on real-world data). Extracted formulas are faithful
  to the model predictions, to the point of providing insights into some occasionally
  incorrect rules learned by the model, making GLGExplainer a promising diagnostic
  tool for learned GNNs.
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Logic in Computer Science
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2210.07147
---
