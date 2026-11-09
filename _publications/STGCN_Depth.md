---
title: "Efficient Traffic Prediction at Scale: A Systematic Study of STGCN Architectural Depth"
collection: publications
permalink: /publication/STGCN_Depth
excerpt: 'We ask whether spatio-temporal graph neural networks for traffic prediction are over-parameterized, using STGCN as a test case. Across four traffic datasets, a single-block STGCN matches or beats the standard 2-block design at a fraction of the computational cost.'
date: 2026-06-08
venue: 'Accepted to the 2026 IEEE 29th International Conference on Intelligent Transportation Systems (ITSC), Naples, Italy'
paperurl: 'https://arxiv.org/abs/2606.09539'
citation: 'Lone, Soban Nasir, Mohamed Abouelela, Taeyoung Yu, Jiwon Kim, and Constantinos Antoniou. "Efficient Traffic Prediction at Scale: A Systematic Study of STGCN Architectural Depth." Accepted to the 2026 IEEE 29th International Conference on Intelligent Transportation Systems (ITSC), Naples, Italy. arXiv preprint arXiv:2606.09539 (2026).'
---

Spatio-temporal graph neural networks (STGNNs) have become the dominant approach for traffic prediction, yet their computational requirements pose challenges for practical deployment in intelligent transportation systems (ITS). While recent work has proposed efficient alternatives to STGNNs, a fundamental question remains unexplored: are these architectures themselves over-parameterised? We examine this question using the Spatio-Temporal Graph Convolutional Network (STGCN), one of the most widely adopted models in this domain.

Through systematic experiments across four diverse traffic datasets, we compare 1-block, 2-block (standard), and 3-block STGCN variants. Our findings reveal that the single-block architecture achieves optimal performance for short-term prediction (10 mins) on three of four datasets, while incurring only marginal degradation (≤1.8% relative error) at longer horizons. Crucially, the 2-block variant incurs 61% higher CPU inference latency and 37% lower throughput relative to 1-block -- substantial overhead for resource-constrained ITS deployment. The 3-block architecture offers no favourable tradeoff, more than doubling computational cost for <0.5% relative improvement. These results suggest that the default 2-block STGCN may be over-parameterised for many applications, with implications for both practitioners deploying traffic prediction systems and researchers benchmarking efficiency-focused methods.
