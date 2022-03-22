---
title: "Learning and Generalizing Cooperative Manipulation Skills using Parametric Dynamic Movement Primitives"
categories:
 - Research
 - Journal
tags:
 - real-time
 - monocular
 - depth estimation
header:
  teaser: /assets/image/thumbnail/IJCAS2021.jpg
conference: TASE
authors: <u>Hyoin Kim</u>, Changsuk Oh, Inkyu Jang, Sungyong Park, Hoseong Seo, H Jin Kim
links:
 - paper: 
   link: https://ieeexplore.ieee.org/abstract/document/9686040
   name: "Paper"
 - video:
   link: https://www.youtube.com/watch?v=xw5C1FYHHLU
   name: "Video"
 - bibtex: 
   name: "Bibtex"
---

{% include video id="xw5C1FYHHLU" provider="youtube" %}

**Abstract:** This paper presents an approach that generates the overall trajectory of mobile manipulators for a complex mission consisting of several sub-tasks. Parametric dynamic movement primitives (PDMPs) can quickly generalize the online motion of robot manipulation by learning multiple demonstrations in offline. However, regarding complex missions consisting of multiple sub-tasks, a large number of demonstrations are required for full generalization, which is impractical. In this paper, we propose a framework that reduces the number of demonstrations for a complex mission. In the proposed method, complex demonstrations are segmented into multiple unit motions representing sub-tasks, and one PDMP is formed per each segment, resulting in multiple PDMPs. The phase decision process determines which sub-task and associated PDMPs to be executed online, allowing multiple PDMPs to be autonomously configured within an integrated framework. In order to generalize the execution time and regional goal in each phase, the Gaussian process regression (GPR) is applied. Simulation results from two different scenarios confirm that the proposed framework not only effectively reduces the number of demonstrations but also improves generalization performance. The actual experiments also demonstrate that the mobile manipulators effectively perform complex missions through the proposed framework.
## Bibtex <a id="bibtex"></a>
```
@article{kim2022learning,
  title={Learning and Generalizing Cooperative Manipulation Skills Using Parametric Dynamic Movement Primitives},
  author={Kim, Hyoin and Oh, Changsuk and Jang, Inkyu and Park, Sungyong and Seo, Hoseong and Kim, H Jin},
  journal={IEEE Transactions on Automation Science and Engineering},
  year={2022},
  publisher={IEEE}
}
```
