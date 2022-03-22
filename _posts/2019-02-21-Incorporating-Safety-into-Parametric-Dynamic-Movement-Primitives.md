---
title: "Incorporating Safety into Parametric Dynamic Movement Primitives"
categories:
 - Research
 - Journal
tags:
 - learning from demonstration
 - autonomous aerial vehicle
 - cooperative manipulation
header:
  teaser: /assets/image/thumbnail/RAL2019.png
conference: RAL
authors: <u>Hyoin Kim</u>, Hoseong Seo, Seungwon Choi, Claire J Tomlin, H Jin Kim
links: 
 - paper: 
   link: https://ieeexplore.ieee.org/abstract/document/8648156
   name: "Paper"
 - video:
   link: https://www.youtube.com/watch?v=4A_fqxlJI5Q
   name: "Video"
 - bibtex: 
   name: "Bibtex"
---

{% include video id="4A_fqxlJI5Q" provider="youtube" %}

**Abstract:** Parametric dynamic movement primitives (PDMPs) are powerful motion representation algorithms, which encode multiple demonstrations and generalize them. As an online trajectory from PDMPs emulates the provided demonstrations, managing the safety guarantee of the demonstrations for a given scenario is an important issue. This letter presents a process to manage the demonstration set in PDMPs when some demonstrations are poor in terms of safety. Our proposed process distinguishes safe motion primitives from unsafe ones. In order to establish a criterion for determining whether a motion is safe or not, we calculate the safe region of the PDMPs parameters called style parameters using an optimization technique. In the optimization formulation, we calculate the unsafe style parameters that produce the closest motion to the unsafe region of the state space. By eliminating unsafe demonstrations with the parameters based on the safety criterion, and replacing them with new safe ones, we incorporate safety in the PDMPs framework. Simulation and experimental results validate that the proposed process can expand the motion primitives in the PDMPs framework to the new environmental settings by efficiently utilizing the previous demonstrations.

## Bibtex <a id="bibtex"></a>
```
@article{kim2019incorporating,
  title={Incorporating Safety Into Parametric Dynamic Movement Primitives},
  author={Kim, Hyoin and Seo, Hoseong and Choi, Seungwon and Tomlin, Claire J and Kim, H Jin},
  journal={IEEE Robotics and Automation Letters},
  volume={4},
  number={3},
  pages={2260--2267},
  year={2019},
  publisher={IEEE}
}
```
