---
title: 'IntelliCode compose: code generation using transformer'
authors:
- Alexey Svyatkovskiy
- Shao Kun Deng
- Shengyu Fu
- Neel Sundaresan
date: '2020-11-08'
publishDate: '2024-09-13T09:52:59.325729Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 28th ACM Joint Meeting on European Software Engineering
  Conference and Symposium on the Foundations of Software Engineering*'
abstract: In software development through integrated development environments (IDEs),
  code completion is one of the most widely used features. Nevertheless, majority
  of integrated development environments only support completion of methods and APIs,
  or arguments. In this paper, we introduce IntelliCode Compose – a general-purpose
  multilingual code completion tool which is capable of predicting sequences of code
  tokens of arbitrary types, generating up to entire lines of syntactically correct
  code. It leverages state-of-the-art generative transformer model trained on 1.2
  billion lines of source code in Python, C#, JavaScript and TypeScript programming
  languages. IntelliCode Compose is deployed as a cloud-based web service. It makes
  use of client-side tree-based caching, efficient parallel implementation of the
  beam search decoder, and compute graph optimizations to meet edit-time completion
  suggestion requirements in the Visual Studio Code IDE and Azure Notebook. Our best
  model yields an average edit similarity of 86.7% and a perplexity of 1.82 for Python
  programming language.
tags:
- Code completion
- naturalness of software
- neural networks
links:
- name: URL
  url: https://doi.org/10.1145/3368089.3417058
---