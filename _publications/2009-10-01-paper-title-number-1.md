---
title: "Alpha-VI DeepONet"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'We introduce a novel deep operator network (DeepONet) framework that incorporates generalised
        variational inference (GVI) using Rényi’s α-divergence to learn complex operators while quantifying
        uncertainty. We apply this approach to a range of mechanics problems, including gravity
        pendulum, advection-diffusion, and diffusion-reaction systems.'
date: 2024-08-01
venue: 'arXiv preprint'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2408.00681'
citation: 'S. N. Lone, S. De, R. Nayek, Alpha-VI DeepONet: A prior-robust variational Bayesian approach for enhancing DeepONets with uncertainty quantification, arXiv preprint  arXiv:2408.00681 (2024)'
---

By incorporating Bayesian neural networks as the building blocks for the branch and
trunk networks, our framework endows DeepONet with uncertainty quantification. The use of
Rényi’s α-divergence, instead of the Kullback-Leibler divergence (KLD), commonly used in standard
variational inference, mitigates issues related to prior misspecification that are prevalent in Variational
Bayesian DeepONets. This approach offers enhanced flexibility and robustness. We demonstrate
that modifying the variational objective function yields superior results in terms of minimising the
mean squared error and improving the negative log-likelihood on the test set. Our framework’s
efficacy is validated across various mechanical systems, where it outperforms both deterministic
and standard KLD-based VI DeepONets in predictive accuracy and uncertainty quantification. The
hyperparameter α, which controls the degree of robustness, can be tuned to optimise performance
for specific problems. We apply this approach to a range of mechanics problems, including gravity
pendulum, advection-diffusion, and diffusion-reaction systems. Our findings underscore the potential
of α-VI DeepONet to advance the field of data-driven operator learning and its applications in
engineering and scientific domains. 
![NMSE]("x9.png)"
![NLL]("images/x10.png")

