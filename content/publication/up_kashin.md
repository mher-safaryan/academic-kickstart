---
title: "Uncertainty Principle for Communication Compression  in Distributed and Federated Learning and the Search for an Optimal Compressor"
date: "2020-02-20"
abstract: "In order to mitigate the high communication cost in distributed and federated learning, various vector compression schemes, such as quantization, sparsification and dithering, have become very popular. In designing a compression method, one aims to communicate as few bits as possible, which minimizes the cost per communication round, while at the same time attempting to impart as little distortion (variance) to the communicated messages as possible, which minimizes the adverse effect of the compression on the overall number of communication rounds. However, intuitively, these two goals are fundamentally in conflict: the more compression we allow, the more distorted the messages become. We formalize this intuition and prove an uncertainty principle for randomized compression operators, thus quantifying this limitation mathematically, and effectively providing lower bounds on what might be achievable with communication compression. Motivated by these developments, we call for the search for the optimal compression operator. In an attempt to take a first step in this direction, we construct a new unbiased compression method inspired by the Kashin representation of vectors, which we call Kashin compression (KC). In contrast to all previously proposed compression mechanisms, we prove that KC enjoys a dimension independent variance bound with an explicit formula even in the regime when only a few bits need to be communicate per each vector entry. We show how KC can be provably and efficiently combined with several existing optimization algorithms, in all cases leading to communication complexity improvements on previous state of the art."
authors: ["Mher Safaryan", "Egor Shulgin", "Peter Richtárik"]
math: true
publication: "preprint"
links:
- name: arXiv
  url: https://arxiv.org/abs/2002.08958
- name: "Information and Inference: A Journal of IMA (2021)"
  url: 10.1093/imaiai/iaab006
---
