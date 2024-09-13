---
title: 'Deep learning for case-based reasoning through prototypes: a neural network
  that explains its predictions'
authors:
- Oscar Li
- Hao Liu
- Chaofan Chen
- Cynthia Rudin
date: '2018-02-02'
publishDate: '2024-09-13T09:52:58.764343Z'
publication_types:
- paper-conference
publication: '*Proceedings of the Thirty-Second AAAI Conference on Artificial Intelligence
  and Thirtieth Innovative Applications of Artificial Intelligence Conference and
  Eighth AAAI Symposium on Educational Advances in Artificial Intelligence*'
abstract: 'Deep neural networks are widely used for classification. These deep models
  often suffer from a lack of interpretability - they are particularly difficult to
  understand because of their non-linear nature. As a result, neural networks are
  often treated as \"black box\" models, and in the past, have been trained purely
  to optimize the accuracy of predictions. In this work, we create a novel network
  architecture for deep learning that naturally explains its own reasoning for each
  prediction. This architecture contains an autoencoder and a special prototype layer,
  where each unit of that layer stores a weight vector that resembles an encoded training
  input. The encoder of the autoencoder allows us to do comparisons within the latent
  space, while the decoder allows us to visualize the learned prototypes. The training
  objective has four terms: an accuracy term, a term that encourages every prototype
  to be similar to at least one encoded input, a term that encourages every encoded
  input to be close to at least one prototype, and a term that encourages faithful
  reconstruction by the autoen-coder. The distances computed in the prototype layer
  are used as part of the classification process. Since the prototypes are learned
  during training, the learned network naturally comes with explanations for each
  prediction, and the explanations are loyal to what the network actually computes.'
---