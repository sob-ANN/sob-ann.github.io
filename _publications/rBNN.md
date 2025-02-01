---
title: "Recursive Bayesian neural networks"
collection: publications
permalink: /publication/Alpha_VI_DeepONet
excerpt: 'This study proposes a recursive Bayesian neural network (rBNN) framework for uncertainty-aware constitutive modelling in  geotechnical engineering, incorporating a sliding window approach to capture temporal dependencies. Validated on numerical and experimental triaxial datasets, the rBNN provides robust confidence intervals, highlighting trade-offs between deterministic and probabilistic models.'
date: 2024-08-01
venue: 'arXiv preprint'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2501.10088'
citation: 'Noor, T., Nasir Lone, S., Ramana, G.V. and Nayek, R., 2025. A recursive Bayesian neural network for constitutive modeling of sands under monotonic loading. arXiv e-prints, pp.arXiv-2501.'
---

In geotechnical engineering, constitutive models play a crucial role in describing soil behavior under varying loading conditions. Data-driven deep learning (DL) models offer a promising alternative for developing predictive constitutive models. When prediction is the primary focus, quantifying the predictive uncertainty of a trained DL model and communicating this uncertainty to end users is crucial for informed decision-making.
This study proposes a recursive Bayesian neural network (rBNN) framework, which builds upon recursive feedforward neural networks (rFFNNs) by introducing generalized Bayesian inference for uncertainty quantification. A significant contribution of this work is the incorporation of a sliding window approach in rFFNNs, allowing the models to effectively capture temporal dependencies across load steps. The rBNN extends this framework by treating model parameters as random variables, with their posterior distributions inferred using generalized variational inference.
The proposed framework is validated on two datasets: (i) a numerically simulated consolidated drained (CD) triaxial dataset employing a hardening soil model and (ii) an experimental dataset comprising 28 CD triaxial tests on Baskarp sand. Comparative analyses with LSTM, Bi-LSTM, and GRU models demonstrate that the deterministic rFFNN achieves superior predictive accuracy, attributed to its transparent structure and sliding window design. While the rBNN marginally trails in accuracy for the experimental case, it provides robust confidence intervals, addressing data sparsity and measurement noise in experimental conditions. The study underscores the trade-offs between deterministic and probabilistic approaches and the potential of rBNNs for uncertainty-aware constitutive modeling.
![Simulation data](/images/x8.png)
![Experimental](/images/x14.png)

