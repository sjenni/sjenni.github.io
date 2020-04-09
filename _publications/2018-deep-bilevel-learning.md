---
title: "Deep Bilevel Learning"
collection: publications
permalink: /publication/2018-deep-bilevel-learning
excerpt: 'S. Jenni, and P. Favaro'
date: 2018-01-01
venue: 'European Conference on Computer Vision 2018'
citation: 'S. Jenni, and P. Favaro. &quot;Deep Bilevel Learning.&quot; In <i>ECCV 2018</i>.'
---

 [[PDF]](https://arxiv.org/pdf/1809.01465.pdf) [[Project Page]](https://sjenni.github.io/DeepBilevel/) [[Code]](https://github.com/sjenni/DeepBilevel) 

## Abstract

We present a novel regularization approach to train neural networks that enjoys better generalization and test error than standard stochastic gradient descent. Our approach is based on the principles of cross-validation, where a validation set is used to limit the model overfitting. We formulate such principles as a bilevel optimization problem. This formulation allows us to define the optimization of a cost on the validation set subject to another optimization on the training set. The overfitting is controlled by introducing weights on each mini-batch in the training set and by choosing their values so that they minimize the error on the validation set. In practice, these weights define mini-batch learning rates in a gradient descent update equation that favor gradients with better generalization capabilities. Because of its simplicity, this approach can be integrated with other regularization methods and training schemes. We evaluate extensively our proposed algorithm on several neural network architectures and datasets, and find that it consistently improves the generalization of the model, especially when labels are noisy.
