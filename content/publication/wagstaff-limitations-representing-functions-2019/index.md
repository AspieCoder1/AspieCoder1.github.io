---
title: On the Limitations of Representing Functions on Sets
authors:
- Edward Wagstaff
- Fabian Fuchs
- Martin Engelcke
- Ingmar Posner
- Michael A. Osborne
date: '2019-05-24'
publishDate: '2024-09-13T09:52:59.448557Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 36th International Conference on Machine Learning*'
abstract: Recent work on the representation of functions on sets has considered the
  use of summation in a latent space to enforce permutation invariance. In particular,
  it has been conjectured that the dimension of this latent space may remain fixed
  as the cardinality of the sets under consideration increases. However, we demonstrate
  that the analysis leading to this conjecture requires mappings which are highly
  discontinuous and argue that this is only of limited practical use. Motivated by
  this observation, we prove that an implementation of this model via continuous mappings
  (as provided by e.g. neural networks or Gaussian processes) actually imposes a constraint
  on the dimensionality of the latent space. Practical universal function representation
  for set inputs can only be achieved with a latent dimension at least the size of
  the maximum number of input elements.
links:
- name: URL
  url: https://proceedings.mlr.press/v97/wagstaff19a.html
---
