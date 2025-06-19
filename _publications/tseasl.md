---
title: "Temporally-Sampled Efficiently Adaptive State Lattices for Autonomous Ground Robot Navigation in Partially Observed Environments"
collection: publications
permalink: /publication/tseasl
excerpt: 'This paper discretizes the space of robot states considered during nodeorm graph-based search for unmanned ground vehicles.'
excerpt: 'This paper proposes a motion planning arbitration architecture that considers updated and optimized versions of previously generated trajectories as possible candidates for the local controller's use as a reference trajectory. It is designed to make the regional planner more robust to inherently uncertain perceptual information."
date: 2021-07-09
venue: '19th International Symposium on Experimental Robotics (ISER)'
[//]: # paperurl: 'http://academicpages.github.io/files/paper3.pdf'
paperurl: 'forthcoming'
citation: 'A.S. Menon, E.R. Damm, E.S. Lancaster, F.A. Sanchez, J.M. Gregory, and T.M. Howard. (2025). forthcoming'
---

![alt text](/images/doasl.png)

Robust motion planners for unmanned ground vehicles must minimize risk while obeying vehicle mobility constraints. Algorithms such as the State Lattice (SL) utilize offline computation to generate expressive control sets which form recombinant search spaces, enabling the use of heuristic search to efficiently produce feasible motion plans online. The Adaptive State Lattice (ASL) demonstrated that local optimizations of the continuous states explored by heuristic search can produce lower-cost solutions in less time than more densely sampled unadapted lattices in sufficiently complex environments. However, the computational cost of this online adaptation limits the application of ASL for mobile robot navigation. We present the Efficiently Adaptive State Lattice (EASL), a novel formalism for online discrete ASL adaptation to overcome this limitation. By discretizing the space of states considered during adaptation, EASL limits the set of feasible motions which could arise during search. This permits the precomputation of an approximation of all motions that could be expressed by an ASL. This approximation removes the online trajectory generation component of the ASL while retaining the benefits of lattice adaptation and enables the use of precomputed swaths for evaluating edge costs. Experimental results demonstrate how an EASL-based planner can generate lower-cost paths than a SL-based planner in roughly equal to or less than the same amount of time.

