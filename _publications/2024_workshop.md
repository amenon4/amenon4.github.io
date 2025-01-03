---
title: "Toward Mobile Robot Navigation in Unstructured Environments Using Topology-Aware Efficiently Adaptive State Lattices"
collection: publications
permalink: /publication/2024-taeasl
date: 2024-05-17
excerpt: 'This paper is the initial manuscript which pertains to the homotopy-constraint search algorithm which is more rigorously examined in the above paper.'
venue: '2024 International Conference on Robotics and Automation (ICRA) Workshop on Resilient Off-Road Autonomy'
[//]: # slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://openreview.net/pdf?id=sGPT1ws0Yf'
citation: 'A.S. Menon, E.R. Damm, and T.M. Howard. (2024). &quot;Toward Mobile Robot Navigation in Unstructured Environments Using Topology-Aware Efficiently Adaptive State Lattices.&quot; <i>ICRA 2024 Workshop on Resilient Off-Road Autonomy</i>.'

---

Contemporary mobile robot navigation architectures that employ a planning algorithm to provide a single optimal path to follow are flawed in the presence of dynamic and uncertain environments. As the environment updates and the robot's starting state changes, optimal plans often oscillate around discrete obstacles, which is problematic for path following controllers that are strongly biased to follow the planned route. In this paper, we reformulate the search process employed by Efficiently Adaptive State Lattices (EASL) to exploit homotopy classes extracted from an observed environment. This approach, which we call Topology-Aware Efficiently Adaptive State Lattices (TAEASL), performs heuristic search using multiple data structures to control expansion of nodes in the graph to provide multiple minimum-cost plans in distinct homotopy classes. Inspired by approaches such as Anytime Repairing A-Star, search continues until no further expansions can be performed or a maximum search time has been reached. To validate TAEASL's utility in field robotics, it was tested on real-world, off-road environment data that was collected by a Clearpath Warthog unmanned ground vehicle (UGV) and was able to generate multiple solutions. The paper concludes with a discussion of applications including high-speed off-road mobile robot navigation in cluttered obstacle fields.
