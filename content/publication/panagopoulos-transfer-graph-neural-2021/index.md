---
title: Transfer Graph Neural Networks for Pandemic Forecasting
authors:
- George Panagopoulos
- Giannis Nikolentzos
- Michalis Vazirgiannis
date: '2021-05-18'
publishDate: '2024-09-13T09:52:58.988748Z'
publication_types:
- article-journal
abstract: The recent outbreak of COVID-19 has affected millions of individuals around
  the world and has posed a significant challenge to global healthcare. From the early
  days of the pandemic, it became clear that it is highly contagious and that human
  mobility contributes significantly to its spread. In this paper, we utilize graph
  representation learning to capitalize on the underlying relationship of population
  movement with the spread of COVID-19. Specifically, we create a graph where the
  nodes correspond to a country's regions, the features include the region's history
  of COVID-19, and the edge weights denote human mobility from one region to another.
  Subsequently, we employ graph neural networks to predict the number of future cases,
  encoding the underlying diffusion patterns that govern the spread into our learning
  model. Furthermore, to account for the limited amount of training data, we capitalize
  on the pandemic's asynchronous outbreaks across countries and use a model-agnostic
  meta-learning based method to transfer knowledge from one country's model to another's.
  We compare the proposed approach against simple baselines and more traditional forecasting
  techniques in 4 European countries. Experimental results demonstrate the superiority
  of our method, highlighting the usefulness of GNNs in epidemiological prediction.
  Transfer learning provides the best model, highlighting its potential to improve
  the accuracy of the predictions in case of secondary waves, given data from past/parallel
  outbreaks.
tags:
- AI Responses to the COVID-19 Pandemic (Covid19)
links:
- name: URL
  url: https://ojs.aaai.org/index.php/AAAI/article/view/16616
---