---
title: "On Biased Compression for Distributed Learning"
date: "2020-02-27"
abstract: "In the last few years, various communication  compression techniques have  emerged  as an indispensable  tool helping to alleviate the communication bottleneck in distributed learning. However, despite the fact biased compressors often show superior performance in practice when compared to the much more studied and understood unbiased compressors,  very little is known about them. In this work we study three classes of biased compression operators, two of which are new, and their performance when applied to  (stochastic) gradient descent and distributed (stochastic) gradient descent.  We show for the first time that biased compressors can lead to linear convergence rates both in the single node and distributed settings. Our distributed SGD method  enjoys the ergodic rate O(δL/μ exp(-K) + (C + D)/(Kμ)), where δ is a compression parameter which grows when more compression is applied, L and μ are the smoothness and strong convexity constants, C captures stochastic gradient noise (C=0 if full gradients are computed on each node) and C captures the variance of the gradients at the optimum (C=0 for over-parameterized models).  Further,  via a theoretical study of several synthetic and empirical distributions of communicated gradients, we shed light on why and by how much  biased compressors outperform  their unbiased variants.  Finally, we  propose a new highly performing biased compressor---combination of Top-k and natural dithering---which in our experiments outperforms all other compression techniques."
authors: ["Aleksandr Beznosikov", "Samuel Horváth", "Peter Richtárik", "Mher Safaryan"]
math: true
publication: "preprint"
links:
- name: arXiv
  url: https://arxiv.org/abs/2002.12410
- name: Poster
  url: files/poster_on_Biased_Compression.png
- name: Slides
  url: https://drive.google.com/file/d/1P32f4n-RupsfIEUT-fLciKHzorQWMslf/view
- name: "FLOW Video"
  url: https://www.youtube.com/watch?v=wkfuIbfdh5s&feature=emb_logo&ab_channel=FederatedLearningOneWorldSeminar
- name: "NeurIPS SpicyFL Workshop 2020"
  url: https://neurips.cc/virtual/2020/public/workshop_16123.html
---
