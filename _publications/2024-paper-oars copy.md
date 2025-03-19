---
title: "Optimal Design of Resolvent Splitting Algorithms."
collection: publications
permalink: 2025-paper-snl
excerpt: ''
date: 2025-03-17
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2503.134039'
citation: 'Barkley, P. & Bassett, R. L. (2024). Optimal Design of Resolvent Splitting Algorithms.'
---
In this paper, we introduce a novel semidefinite programming framework for designing custom frugal resolvent splitting algorithms which find a zero in the sum of n monotone operators. This framework features a number of design choices which facilitate creating resolvent splitting algorithms with specific communication structure. We illustrate these design choices using a variety of constraint sets and objective functions, as well as the use of a mixed-integer SDP to minimize time per iteration or required number of communications between the resolvents which define the splitting. Using the Performance Estimation Problem (PEP) framework, we provide parameter selections, such as step size, which for high dimensional problems provide optimal contraction factors in the algorithms. Among the algorithm design choices we introduce, we provide a characterization of algorithm designs which provide minimal convergence time given structural properties of the monotone operators, resolvent computation times, and communication latencies. 

The code supporting the paper can be found at my [Github OARS repo](https://github.com/peterbarkley/oars).

Recommended citation: Bassett, R. L., & Barkley, P. (2024). Optimal Design of Resolvent Splitting Algorithms. https://arxiv.org/abs/2407.16159.