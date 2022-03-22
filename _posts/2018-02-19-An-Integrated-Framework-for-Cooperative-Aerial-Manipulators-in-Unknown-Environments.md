---
title: "An Integrated Framework for Cooperative Aerial Manipulators in Unknown Environments"
categories:
 - Research
 - Journal
tags:
 - planning
 - control
 - learning from demonstration
 - autonomous aerial vehicle
 - cooperative manipulation
header:
  teaser: /assets/image/thumbnail/RAL2018.png
conference: RAL
authors: Hyeonbeom Lee, <u>Hyoin Kim</u>, Woojin Kim, and H. Jin Kim
links: 
 - paper: 
   link: https://ieeexplore.ieee.org/abstract/document/8294245
   name: "Paper"
 - bibtex: 
   name: "Bibtex"
---

**Abstract:** This letter presents a viable framework that integrates control, estimation of unknown payload, safety management, and obstacle avoidance for cooperative transportation in unknown environments using multiple aerial manipulators. Unlike existing approaches for cooperative manipulation based on force decomposition or impedance-based control that often require heavy or expensive force/torque sensors, this letter suggests a method without such sensors, by exploiting the decentralized dynamics. First, an online estimator is designed to estimate the mass and inertial properties of an unknown payload, and an adaptive controller based on the estimated parameter is developed. For planning, trajectory in joint space is generated to satisfy unilateral constraints for safety, and dynamic movement primitives (DMPs) modify the trajectory to avoid obstacles on the fly. By integration of these components, the proposed framework can be executed in real time. The proposed framework is validated with experiments using camera-equipped aerial manipulators combined with a two-degree of freedom robotic arm in environments containing obstacles. Experimental results show that the proposed approach can be utilized for safe cooperative aerial transportation in realistic environments.

## Bibtex <a id="bibtex"></a>
```
@article{lee2018integrated,
  title={An integrated framework for cooperative aerial manipulators in unknown environments},
  author={Lee, Hyeonbeom and Kim, Hyoin and Kim, Woojin and Kim, H Jin},
  journal={IEEE Robotics and Automation Letters},
  volume={3},
  number={3},
  pages={2307--2314},
  year={2018},
  publisher={IEEE}
}
```



