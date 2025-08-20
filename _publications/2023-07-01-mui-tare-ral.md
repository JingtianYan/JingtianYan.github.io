---
title: "MUI-TARE: Cooperative Multi-Agent Exploration With Unknown Initial Position"
collection: publications
category: "2023"
permalink: /publication/2023-07-01-mui-tare-ral
authors: "Jingtian Yan, Xingqiao Lin, Zhongqiang Ren, Shiqi Zhao, Jieqiong Yu, Chao Cao, Peng Yin, Ji Zhang, Sebastian Scherer"
# excerpt: 'Multi-agent exploration of a bounded 3D environment with the unknown initial poses of agents is a challenging problem. To intelligently balance the robustness of sub-map merging and exploration efficiency, we develop a new approach for lidar-based multi-agent exploration that improves exploration efficiency by up to 50% while merging sub-maps robustly.'
date: 2023-07-01
venue: 'IEEE Robotics and Automation Letters (RA-L)'
paperurl: 'https://arxiv.org/pdf/2209.10775.pdf'
bibtexurl: '/files/mui-tare-ral-2023.bib'
videourl: 'https://www.youtube.com/watch?v=imSKHg3T1Wo'
bibtex: |
  @article{yan2023muitare,
    title={MUI-TARE: Cooperative Multi-Agent Exploration With Unknown Initial Position},
    author={Yan, Jingtian and Lin, Xingqiao and Ren, Zhongqiang and Zhao, Shiqi and Yu, Jieqiong and Cao, Chao and Yin, Peng and Zhang, Ji and Scherer, Sebastian},
    journal={IEEE Robotics and Automation Letters},
    volume={8},
    number={7},
    pages={4299--4306},
    year={2023},
    publisher={IEEE},
    doi={10.1109/LRA.2023.3281262}
  }
citation: 'Jingtian Yan, Xingqiao Lin, Zhongqiang Ren, Shiqi Zhao, Jieqiong Yu, Chao Cao, Peng Yin, Ji Zhang, and Sebastian Scherer. <i>IEEE Robotics and Automation Letters</i>. 8(7), 4299-4306, 2023.'
---

## Demo Video

<video width="100%" controls>
  <source src="/files/mui-tare-demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

Multi-agent exploration of a bounded 3D environment with the unknown initial poses of agents is a challenging problem. It requires both quickly exploring the environments and robustly merging the sub-maps built by the agents. Most existing exploration strategies directly merge two sub-maps built by different agents when a single frame observation is matched, which can lead to incorrect merging due to the false-positive detection of the overlap and is thus not robust. 

In the meanwhile, some recent place recognition methods use sequence matching for robust data association. However, naively applying these sequence matching methods to multi-agent exploration may require one agent to repeat a large amount of another agent's history trajectory so that a sequence of matched observation can be established, which reduces the overall exploration time efficiency. 

To intelligently balance the robustness of sub-map merging and exploration efficiency, we develop a new approach for lidar-based multi-agent exploration, which can direct one agent to repeat another agent's trajectory in an adaptive manner based on the quality indicator of the sub-map merging process. Additionally, our approach extends the recent single-agent hierarchical exploration strategy to multiple agents in a cooperative manner for agents whose sub-maps are merged, to improve exploration efficiency. Our experiments show that our approach is up to 50% more efficient than the baselines while merging sub-maps robustly.

**Links:**
- [Paper (arXiv)](https://arxiv.org/abs/2209.10775)
- [Video](https://www.youtube.com/watch?v=imSKHg3T1Wo)
- [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10138598)

## BibTeX

```bibtex
@article{yan2023muitare,
  title={MUI-TARE: Cooperative Multi-Agent Exploration With Unknown Initial Position},
  author={Yan, Jingtian and Lin, Xingqiao and Ren, Zhongqiang and Zhao, Shiqi and Yu, Jieqiong and Cao, Chao and Yin, Peng and Zhang, Ji and Scherer, Sebastian},
  journal={IEEE Robotics and Automation Letters},
  volume={8},
  number={7},
  pages={4299--4306},
  year={2023},
  publisher={IEEE},
  doi={10.1109/LRA.2023.3281262}
}
```
