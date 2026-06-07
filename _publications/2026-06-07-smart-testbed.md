---
title: "Advancing MAPF Toward the Real World: A Scalable Multi-Agent Realistic Testbed (SMART)"
collection: publications
category: "2026"
permalink: /publication/2026-06-07-smart-testbed
redirect_from:
  - /publication/2025-03-02-smart-testbed
authors: "Jingtian Yan, Zhifei Li, William Kang, Kevin Zheng, Yulun Zhang, Zhe Chen, Yue Zhang, Daniel Harabor, Stephen F. Smith, Jiaoyang Li"
# excerpt: 'We present SMART, a scalable multi-agent realistic testbed for advancing MAPF research towards real-world applications. This work addresses the gap between theoretical MAPF algorithms and practical deployment challenges.<br/><img src="/images/smart_testbed_preview.png">'
date: 2026-06-07
venue: 'IEEE Robotics and Automation Letters (RA-L)'
paperurl: 'https://ieeexplore.ieee.org/document/11495177'
paperlabel: 'IEEE Xplore'
bibtexurl: '/files/smart-testbed-2026-06-07.bib'
bibtex: |
  @article{yan2026smart,
    title={Advancing MAPF Toward the Real World: A Scalable Multi-Agent Realistic Testbed (SMART)},
    author={Yan, Jingtian and Li, Zhifei and Kang, William and Zheng, Kevin and Zhang, Yulun and Chen, Zhe and Zhang, Yue and Harabor, Daniel and Smith, Stephen F. and Li, Jiaoyang},
    journal={IEEE Robotics and Automation Letters},
    volume={11},
    number={6},
    pages={7428--7435},
    year={2026},
    month={June},
    doi={10.1109/LRA.2026.3688062}
  }
codeurl: 'https://github.com/smart-mapf/smart.git'
videourl: 'https://youtu.be/TX-oGSgM8VQ'
citation: 'Jingtian Yan, Zhifei Li, William Kang, Kevin Zheng, Yulun Zhang, Zhe Chen, Yue Zhang, Daniel Harabor, Stephen F. Smith, and Jiaoyang Li. <i>IEEE Robotics and Automation Letters</i>. 11(6), 7428-7435, 2026.<br />ICAPS 2025 Best Demo Award; will present at IROS 2026.'
header:
  teaser: /images/smart_testbed_preview.png
---


**Highlights:** ICAPS 2025 Best Demo Award; will present at IROS 2026.

### [Use Our Online Interface](https://smart-mapf.github.io/demo/)

### Demo Video

<div style="position: relative; width: 100%; max-width: 800px; margin: 20px auto;">
  <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <iframe src="https://www.youtube.com/embed/TX-oGSgM8VQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
  </div>
</div>

## Overview

This work presents SMART, a comprehensive testbed designed to bridge the gap between Multi-Agent Path Finding (MAPF) research and real-world applications. State-of-the-art MAPF algorithms can plan paths for hundreds of robots within seconds.
However, these algorithms make several simplifying assumptions.
First, they rely on simplified robot models that ignore kinodynamic constraints while planning the robots' paths.
Second, they assume that robots can execute these paths perfectly, without accounting for uncertainties introduced by real-world factors.

SMART fills this gap with several advantages:
- SMART uses physics-engine-based simulators to create realistic simulation environments, accounting for complex real-world factors such as robot kinodynamics and execution uncertainties.
- SMART uses an execution monitor framework based on the Action Dependency Graph, facilitating seamless integration with various MAPF algorithms and robot models.
- SMART scales to thousands of robots.

<div style="text-align: center; margin: 20px 0;">
  <video controls style="width: 80%; max-width: 800px;">
    <source src="/images/SMART-Teaser-web.mp4" type="video/mp4">
    Your browser does not support the video tag. <a href="/images/SMART-Teaser-web.mp4">Download video</a>
  </video>
</div>

## Key Features

SMART provides a scalable and realistic testing environment that incorporates real-world constraints and scenarios, enabling researchers to evaluate and improve MAPF algorithms for practical applications. The testbed addresses key limitations in existing evaluation frameworks and provides a more comprehensive assessment of algorithm performance in realistic settings.



### Results Gallery

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin: 20px 0;">
  <div style="text-align: center; flex: 1; min-width: 300px;">
    <img src="/images/SMART-isaac-sim.png" alt="Benchmark Results" style="width: 400px; height: 300px; object-fit: contain; border: 1px solid #ddd; border-radius: 4px;">
    <br><em>Isaac Sim</em>
  </div>
  
  <div style="text-align: center; flex: 1; min-width: 300px;">
    <img src="/images/SMART-real-robot.png" alt="Scalability Analysis" style="width: 400px; height: 300px; object-fit: contain; border: 1px solid #ddd; border-radius: 4px;">
    <br><em>Real Robots</em>
  </div>
</div>

**Links:**
- [Paper (IEEE Xplore)](https://ieeexplore.ieee.org/document/11495177)
- [Preprint (arXiv)](https://arxiv.org/abs/2503.04798)
- [Project Page](/portfolio/smart-testbed/)
- [Code](https://github.com/smart-mapf/smart)
- [MovingAI MAPF Benchmarks](https://movingai.com/benchmarks/mapf/index.html)

## BibTeX

```bibtex
@article{yan2026smart,
  title={Advancing MAPF Toward the Real World: A Scalable Multi-Agent Realistic Testbed (SMART)},
  author={Yan, Jingtian and Li, Zhifei and Kang, William and Zheng, Kevin and Zhang, Yulun and Chen, Zhe and Zhang, Yue and Harabor, Daniel and Smith, Stephen F. and Li, Jiaoyang},
  journal={IEEE Robotics and Automation Letters},
  volume={11},
  number={6},
  pages={7428--7435},
  year={2026},
  month={June},
  doi={10.1109/LRA.2026.3688062}
}
```
