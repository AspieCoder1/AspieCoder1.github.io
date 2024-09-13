---
title: 'SequenceR: Sequence-to-Sequence Learning for End-to-End Program Repair'
authors:
- Zimin Chen
- Steve Kommrusch
- Michele Tufano
- Louis-Noël Pouchet
- Denys Poshyvanyk
- Martin Monperrus
date: '2021-09-01'
publishDate: '2024-09-13T09:52:57.955296Z'
publication_types:
- article-journal
publication: '*IEEE Computer Society*'
abstract: This paper presents a novel end-to-end approach to program repair based
  on sequence-to-sequence learning. We devise, implement, and evaluate a technique,
  called SequenceR, for fixing bugs based on sequence-to-sequence learning on source
  code. This approach uses the copy mechanism to overcome the unlimited vocabulary
  problem that occurs with big code. Our system is data-driven; we train it on 35,578
  samples, carefully curated from commits to open-source repositories. We evaluate
  SequenceR on 4,711 independent real bug fixes, as well on the Defects4J benchmark
  used in program repair research. SequenceR is able to perfectly predict the fixed
  line for 950/4,711 testing samples, and find correct patches for 14 bugs in Defects4J
  benchmark. SequenceR captures a wide range of repair operators without any domain-specific
  top-down design.
links:
- name: URL
  url: https://www.computer.org/csdl/journal/ts/2021/09/08827954/1ddbmnbiydi
---
