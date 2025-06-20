---
title: "Temporally-Sampled Efficiently Adaptive State Lattices for Autonomous Ground Robot Navigation in Partially Observed Environments"
collection: publications
permalink: /publication/2025-tseasl
date: 2025-07-09
excerpt: 'This paper proposes a robot motion planning arbitration architecture which selects one of multiple candidate trajectories to pass down to the path-following controller. It is used to reduce the burden of safe navigation on the controller in partially observable environments that are prone to perceptual changes.'
venue: '19th International Symposium on Experimental Robotics (ISER)'
[//]: # slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
citation: 'A.S. Menon, E.R. Damm, E.S. Lancaster, F.A. Sanchez, J.M. Gregory, and T.M. Howard. (2025, forthcoming). &quot;Temporally-Sampled Efficiently Adaptive State Lattices for Autonomous Ground Robot Navigation in Partially Observed Environments.&quot; <i>19th International Symposium on Experimental Robotics (ISER)</i>.'

---
![alt text](/images/tseasl.png)

Due to sensor limitations, environments that off-road mobile robots operate in are often only partially observable. As the robots move throughout the environment and towards their goal, the optimal route is continuously revised as the sensors perceive new information. In traditional autonomous navigation architectures, a regional motion planner will consume the environment map and output a trajectory for the local motion planner to use as a reference. Due to the continuous revision of the regional plan guidance as a result of changing map information, the reference trajectories which are passed down to the local planner can differ significantly across sequential planning cycles. This rapidly changing guidance can result in unsafe navigation behavior, often requiring manual safety interventions during autonomous traversals in off-road environments. To remedy this problem, we propose Temporally-Sampled Efficiently Adaptive State Lattices (TSEASL), which is a regional planner arbitration architecture that considers updated and optimized versions of previously generated trajectories against the currently generated trajectory. When tested on a Clearpath Robotics Warthog Unmanned Ground Vehicle as well as real map data collected from the Warthog, results indicate that when running TSEASL, the robot did not require manual interventions in the same locations where the robot was running the baseline planner. Additionally, higher levels of planner stability were recorded with TSEASL over the baseline. The paper concludes with a discussion of further improvements to TSEASL in order to make it more generalizable to various off-road autonomy scenarios.
