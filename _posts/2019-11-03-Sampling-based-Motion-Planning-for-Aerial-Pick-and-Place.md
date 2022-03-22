---
title: "Sampling-based Motion Planning for Aerial Pick-and-Place"
categories:
 - Research
 - Conference
tags:
 - planning
 - autonomous aerial vehicle
header:
  teaser: /assets/image/thumbnail/IROS2019.jpg
conference: IROS
authors: <u>Hyoin Kim</u>, Hoseong Seo, Jongchan Kim, H Jin Kim
links: 
 - paper: 
   link: https://ieeexplore.ieee.org/abstract/document/8967922
   name: "Paper"
 - video:
   link: https://www.youtube.com/watch?v=SIQsg_ZK0z8
   name: "Video"
 - bibtex: 
   name: "Bibtex"
---

{% include video id="SIQsg_ZK0z8" provider="youtube" %}

**Abstract:** This paper presents a motion planning approach for an aerial pick-and-place task where an aerial manipulator is supposed to pick up or place an object at locations specified as way-points. In particular, we focus on situations where such way-point constraints are imposed on certain partial state variables, rather than on full state variables. Our proposed framework, based on rapidly exploring random trees star (RRT * ) in a bidirectional manner, enables an aerial manipulator to find an optimal trajectory that satisfies way-point constraints with only partial specifications. Here, we suggest an extra merging process to integrate the trees, each originated from the start and goal point. In the merging process, we search various candidate points satisfying a given condition that partially constrains state variables, and select a way-point with full specifications optimal in the perspective of the entire trajectory. Simulation and experiment results are included to validate the proposed framework.

## Bibtex <a id="bibtex"></a>
```
@inproceedings{kim2019sampling,
  title={Sampling-based motion planning for aerial pick-and-place},
  author={Kim, Hyoin and Seo, Hoseong and Kim, Jongchan and Kim, H Jin},
  booktitle={2019 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={7402--7408},
  year={2019},
  organization={IEEE}
}
}
```
