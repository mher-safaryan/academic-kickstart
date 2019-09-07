---
title: "On Stochastic Sign Descent Methods"
date: "2019-05-30"
draft: true
abstract: "Various gradient compression schemes have been proposed to mitigate the communication cost in distributed training of large scale machine learning models. Sign-based methods, such as signSGD, have recently been gaining popularity because of their simple compression rule and connection to adaptive gradient methods, like ADAM. In this paper, we perform a general analysis of sign-based methods for non-convex optimization. Our analysis is built on intuitive bounds on success probabilities and does not rely on special noise distributions nor on the boundedness of the variance of stochastic gradients. Extending the theory to distributed setting within a parameter server framework, we assure variance reduction with respect to number of nodes, maintaining 1-bit compression in both directions and using small mini-batch sizes. We validate our theoretical findings experimentally."
authors: ["Mher Safaryan", "Peter Richtárik"]
math: true
publication: "preprint"
url_pdf: "https://arxiv.org/pdf/1905.12938.pdf"
---
