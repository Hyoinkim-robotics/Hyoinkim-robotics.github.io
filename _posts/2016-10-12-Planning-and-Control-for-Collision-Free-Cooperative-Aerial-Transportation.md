---
title: "Planning and Control for Collision-free Cooperative Aerial Transportation"
categories:
 - Research
 - Journal
tags:
 - planning
 - control
 - unmanned aerial vehicle
 - cooperative manipulation
header:
  teaser: /assets/image/thumbnail/TASE2016.png
conference: TASE
authors: Hyeonbeom Lee, <u>Hyoin Kim</u> and H. Jin Kim
links: 
 - paper: 
   link: https://ieeexplore.ieee.org/abstract/document/7589023
   name: "Paper"
 - bibtex: 
   name: "Bibtex"
---

{% include video id="v-2q4XaHWSY" provider="youtube" %}

**Abstract:** This paper presents planning and control synthesis for multiple aerial manipulators to transport a common object. Each aerial manipulator that consists of a hexacopter and a two-degree-of-freedom robotic arm is controlled by an augmented adaptive sliding mode controller based on a closed-chain robot dynamics. We propose a motion planning algorithm by exploiting rapidly exploring random tree star (RRT*) and dynamic movement primitives (DMPs). The desired path for each aerial manipulator is obtained by using RRT* with Bezier curve, which is designed to handle environmental obstacles, such as buildings or equipments. During aerial transportation, to avoid unknown obstacle, DMPs modify the trajectory based on the virtual leader- follower structure. By the combination of RRT* and DMPs, the cooperative aerial manipulators can carry a common object to keep reducing the interaction force between multiple robots while avoiding an obstacle in the unstructured environment. To validate the proposed planning and control synthesis, two experiments with multiple custom-made aerial manipulators are presented, which involve user-guided trajectory and RRT*-planned trajectory tracking in unstructured environments.

## Bibtex <a id="bibtex"></a>
```
@article{lee2016planning,
  title={Planning and control for collision-free cooperative aerial transportation},
  author={Lee, Hyeonbeom and Kim, Hyoin and Kim, H Jin},
  journal={IEEE Transactions on Automation Science and Engineering},
  volume={15},
  number={1},
  pages={189--201},
  year={2016},
  publisher={IEEE}
}
```
