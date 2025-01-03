---
title: "Discrete Optimization of Adaptive State Lattices for Iterative Motion Planning on Unmanned Ground Vehicles"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper discretizes the space of robot states considered during node adaptation in order to more efficiently perform graph-based search for unmanned ground vehicles.'
date: 2021-10
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
[//]: # paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'B. Hedegaard, E Fahnestock, J. Arkin, A. Menon, and T.M. Howard. (2021). &quot;Discrete Optimization of Adaptive State Lattices for Iterative Motion Planning on Unmanned Ground Vehicles&quot; <i>2021 IEEE/RSJ International Conference on Intelligent Robots and Systems</i>. pp. 5764-5771.'
---

Robust motion planners for unmanned ground vehicles must minimize risk while obeying vehicle mobility constraints. Algorithms such as the State Lattice (SL) utilize offline computation to generate expressive control sets which form recombinant search spaces, enabling the use of heuristic search to efficiently produce feasible motion plans online. The Adaptive State Lattice (ASL) demonstrated that local optimizations of the continuous states explored by heuristic search can produce lower-cost solutions in less time than more densely sampled unadapted lattices in sufficiently complex environments. However, the computational cost of this online adaptation limits the application of ASL for mobile robot navigation. We present the Efficiently Adaptive State Lattice (EASL), a novel formalism for online discrete ASL adaptation to overcome this limitation. By discretizing the space of states considered during adaptation, EASL limits the set of feasible motions which could arise during search. This permits the precomputation of an approximation of all motions that could be expressed by an ASL. This approximation removes the online trajectory generation component of the ASL while retaining the benefits of lattice adaptation and enables the use of precomputed swaths for evaluating edge costs. Experimental results demonstrate how an EASL-based planner can generate lower-cost paths than a SL-based planner in roughly equal to or less than the same amount of time.

