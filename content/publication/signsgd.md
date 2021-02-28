---
title: "Stochastic Sign Descent Methods: New Algorithms and Better Theory"
date: "2019-05-30"
abstract: "Various gradient compression schemes have been proposed to mitigate the communication cost in distributed training of large scale machine learning models. Sign-based methods, such as signSGD, have recently been gaining popularity because of their simple compression rule and connection to adaptive gradient methods, like ADAM. In this paper, we analyze sign-based methods for non-convex optimization in three key settings: (i) standard single node, (ii) parallel with shared data and (iii) distributed with partitioned data. For single machine case, we generalize the previous analysis of signSGD relying on intuitive bounds on success probabilities and allowing even biased estimators. Furthermore, we extend the analysis to parallel setting within a parameter server framework, where exponentially fast noise reduction is guaranteed with respect to number of nodes, maintaining 1-bit compression in both directions and using small mini-batch sizes. Next, we identify a fundamental issue with signSGD to converge in distributed environment. To resolve this issue, we propose a new sign-based method, {\em Stochastic Sign Descent with Momentum (SSDM)}, which converges under standard bounded variance assumption with the optimal asymptotic rate. We validate several aspects of our theoretical findings with numerical experiments."
authors: ["Mher Safaryan", "Peter Richtárik"]
math: true
publication: "preprint"
links:
- name: arXiv
  url: https://arxiv.org/pdf/1905.12938
- name: Poster
  url: files/poster_signsgd.png
- name: "NeurIPS OPTML Workshop 2020"
  url: https://opt-ml.org/papers.html
---
