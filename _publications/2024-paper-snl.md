---
title: "Decentralized Sensor Network Localization using Matrix-Parametrized Proximal Splittings."
collection: publications
permalink: 2025-paper-snl
excerpt: ''
date: 2025-03-17
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2503.134039'
citation: 'Bassett, R. L., & Barkley, P. (2024). Decentralized Sensor Network Localization using Matrix-Parametrized Proximal Splittings.'
---
We present a novel application of a recently-proposed matrix-parametrized proximal splitting method to sensor network localization, the problem of estimating the locations of a set of sensors using only noisy pairwise distance information between the sensors. The decentralized computation required by our approach respects the communication structure between sensors specified by the noisy SNL problem, thereby allowing individual sensors to estimate their location using only local computations and communication with their neighbors. Our proposed method experimentally outperforms a competing method for decentralized computation -- the alternating direction method of multipliers (ADMM) -- with respect to convergence rate and memory use. As an independent methodological contribution, we propose using the Sinkhorn-Knopp algorithm in a completely decentralized manner to construct the matrices which parametrize our proposed splitting method. We show that parameters selected using this method perform similarly to those selected via existing parameter selection methods while requiring far less computation. Unlike centralized interior point solution methods, our first order splitting method allows for efficient warm starting, and we demonstrate improvements in convergence using rough estimates of sensor location to warm start our algorithm. We also find that early termination of the algorithm provides more accurate location estimates than the minimizer of the node-based SDP relaxation of the SNL.

The code supporting the paper can be found at my [Github SNL repo](https://github.com/peterbarkley/snl).

Recommended citation: Bassett, R. L., & Barkley, P. (2024). Decentralized Sensor Network Localization using Matrix-Parametrized Proximal Splittings. https://arxiv.org/abs/2503.134039.