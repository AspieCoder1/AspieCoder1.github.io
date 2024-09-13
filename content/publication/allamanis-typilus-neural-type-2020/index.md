---
title: 'Typilus: neural type hints'
authors:
- Miltiadis Allamanis
- Earl T. Barr
- Soline Ducousso
- Zheng Gao
date: '2020-06-11'
publishDate: '2024-09-13T09:52:57.670397Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 41st ACM SIGPLAN Conference on Programming Language
  Design and Implementation*'
abstract: Type inference over partial contexts in dynamically typed languages is challenging.
  In this work, we present a graph neural network model that predicts types by probabilistically
  reasoning over a program’s structure, names, and patterns. The network uses deep
  similarity learning to learn a TypeSpace — a continuous relaxation of the discrete
  space of types — and how to embed the type properties of a symbol (i.e. identifier)
  into it. Importantly, our model can employ one-shot learning to predict an open
  vocabulary of types, including rare and user-defined ones. We realise our approach
  in Typilus for Python that combines the TypeSpace with an optional type checker.
  We show that Typilus accurately predicts types. Typilus confidently predicts types
  for 70% of all annotatable symbols; when it predicts a type, that type optionally
  type checks 95% of the time. Typilus can also find incorrect type annotations; two
  important and popular open source libraries, fairseq and allennlp, accepted our
  pull requests that fixed the annotation errors Typilus discovered.
tags:
- deep learning
- graph neural networks
- meta-learning
- structured learning
- type inference
links:
- name: URL
  url: https://doi.org/10.1145/3385412.3385997
---
