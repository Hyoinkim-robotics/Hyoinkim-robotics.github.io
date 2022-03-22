---
title: "[ICRA2017] Motion Planning with Movement Primitives for Cooperative Aerial Transportation in Obstacle Environment"
categories:
 - Research
 - Conference
tags:
 - planning
 - learning from demonstration 
 - unmanned aerial vehicle
 - cooperative manipulation
header:
  teaser: /assets/image/thumbnail/ICRA2017.png
conference: ICRA
authors: <u>Hyoin Kim</u>, Hyeonbeom Lee, Seungwon Choi, Yung-Kyun Noh, H Jin Kim
links: 
 - paper: 
   link: https://ieeexplore.ieee.org/abstract/document/7989269
   name: "Paper"
 - video:
   link: https://youtu.be/O-veM7IohpQ
   name: "Video"
 - bibtex: 
   name: "Bibtex"
excerpt: "This paper presents a motion planning approach for cooperative transportation using aerial robots. We describe a framework based on Parametric Dynamic Movement Primitives (PDMPs) for coordinating multiple aerial robots and their manipulators quickly in an environment cluttered with obstacles. In order to emulate the optimal motion, we combine PDMPs and Rapidly Exploring Randomized Trees star (RRT*) by using the results of RRT* as demonstrations for PDMPs. For efficient description of the motions corresponding to the environment, we utilize Gaussian Process Regression (GPR) to acquire of the explicit relationship between environmental parameters and style parameters of PDMPs which decide the motions. Simulation and experiment results are attached to validate the proposed framework."
---

{% include video id="O-veM7IohpQ" provider="youtube" %}

**Abstract:** This paper presents a motion planning approach for cooperative transportation using aerial robots. We describe a framework based on Parametric Dynamic Movement Primitives (PDMPs) for coordinating multiple aerial robots and their manipulators quickly in an environment cluttered with obstacles. In order to emulate the optimal motion, we combine PDMPs and Rapidly Exploring Randomized Trees star (RRT*) by using the results of RRT* as demonstrations for PDMPs. For efficient description of the motions corresponding to the environment, we utilize Gaussian Process Regression (GPR) to acquire of the explicit relationship between environmental parameters and style parameters of PDMPs which decide the motions. Simulation and experiment results are attached to validate the proposed framework.

This paper has been selected as <font color='red'><b>one of the finalists of Best Student Paper Award</b></font> of ICRA 2017.

## Bibtex <a id="bibtex"></a>
```
@inproceedings{kim2017motion,
  title={Motion planning with movement primitives for cooperative aerial transportation in obstacle environment},
  author={Kim, Hyoin and Lee, Hyeonbeom and Choi, Seungwon and Noh, Yung-Kyun and Kim, H Jin},
  booktitle={2017 IEEE international conference on robotics and automation (ICRA)},
  pages={2328--2334},
  year={2017},
  organization={IEEE}
}
```



