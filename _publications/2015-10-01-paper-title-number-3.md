---
title: "Homotopy-Aware Efficiently Adaptive State Lattices for Mobile Robot Motion Planning in Cluttered Environments"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper leverages homotopy constraints extracted from the surrounding environment in order to provide motion plans that ease the burden of path-following controllers for mobile robot navigation.'
date: 2025-02-01
venue: 'IEEE Robotics and Automation Letters'
[//]: # slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://ieeexplore.ieee.org/document/10803070'
citation: 'A.S. Menon, E.R. Damm, and T.M. Howard. (2025). &quot;Homotopy-Aware Efficiently Adaptive State Lattices for Mobile Robot Motion Planning in Cluttered Environments.&quot; <i>IEEE Robotics and Automation Letters</i>. vol. 10, no. 2, pp. 947-954.'

---

![alt text](https://github.com/amenon4/amenon4.github.io/blob/master/images/foo-bar-identity.jpg)

Mobile robot navigation architectures that employ a planning algorithm to provide a single optimal path to follow are flawed in the presence of unstructured, rapidly changing environments. As the environment updates, optimal plans often oscillate around discrete obstacles, which is problematic for path following controllers that are biased to follow the planned route. A potentially better approach involves the generation of multiple plans, each optimal within their own homotopy class, to provide a more comprehensive approximation of cost to goal for a path-following controller. In this paper, we present Homotopy-Aware Efficiently Adaptive State Lattices (HAEASL), which uses multiple open lists to bias search towards routes with distinct homotopy classes. Experiments are presented that measure the number, the optimality, and the diversity of solutions generated across 3,200 planning problems in 80 randomly generated environments. The performance of HAEASL is benchmarked against two previous approaches: Search-Based Path Planning with Homotopy Class Constraints (A-Star HC) and Homotopy-Aware RRT-Star (HARRT-Star). Experimental results demonstrate that HAEASL can generate a greater number of paths and more diverse paths than A-Star HC without a significant reduction of optimality. Additionally, results demonstrate that HAEASL generates a greater number of paths and ones with lower costs than HARRT-Star. A final demonstration of HAEASL generating multiple solutions subject to temporal, resource, and kinodynamic constraints using data collected from an off-road mobile robot illustrates the suitability of the approach for the motivating example.
