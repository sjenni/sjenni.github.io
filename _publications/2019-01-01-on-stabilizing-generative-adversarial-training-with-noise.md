---
title: "On Stabilizing Generative Adversarial Training with Noise"
collection: publications
permalink: /publication/2019-01-01-on-stabilizing-generative-adversarial-training-with-noise
date: 2019-01-01
venue: 'IEEE Conference on Computer Vision and Pattern Recognition 2019'
citation: 'S. Jenni, and P. Favaro. &quot;On Stabilizing Generative Adversarial Training with Noise.&quot; In <i>CVPR 2019</i>.'

---

 [[PDF]](https://arxiv.org/pdf/1906.04612.pdf) [[Project Page]](https://sjenni.github.io/dfgan/) [[Code]](https://github.com/sjenni/dfgan) 


## Abstract

We present a novel method and analysis to train generative adversarial networks (GAN) in a stable manner. As shown in recent analysis, training is often undermined by the probability distribution of the data being zero on neighborhoods of the data space. We notice that the distributions of real and generated data should match even when they undergo the same filtering. Therefore, to address the limited support problem we propose to train GANs by using different filtered versions of the real and generated data distributions. In this way, filtering does not prevent the exact matching of the data distribution, while helping training by extending the support of both distributions. As filtering we consider adding samples from an arbitrary distribution to the data, which corresponds to a convolution of the data distribution with the arbitrary one. We also propose to learn the generation of these samples so as to challenge the discriminator in the adversarial training. We show that our approach results in a stable and well-behaved training of even the original minimax GAN formulation. Moreover, our technique can be incorporated in most modern GAN formulations and leads to a consistent improvement on several common datasets.
