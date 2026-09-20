---
title: "From Discrete Plans to Real-World Execution: A World-Model-Driven Framework for Execution-Aware Multi-Agent Path Finding"
collection: publications
category: "2026"
permalink: /publication/2026-06-21-exectimenet
redirect_from:
  - /publication/2025-11-26-exectimenet
authors: "Jingtian Yan, Shuai Zhou, He Jiang, Stephen F. Smith, Jiaoyang Li"
date: 2026-06-21
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2511.21886'
bibtexurl: '/files/exectimenet-2026-06-21.bib'
bibtex: |
  @article{yan2025exectimenet,
    title={From Discrete Plans to Real-World Execution: A World-Model-Driven Framework for Execution-Aware Multi-Agent Path Finding},
    author={Yan, Jingtian and Zhou, Shuai and Jiang, He and Smith, Stephen F. and Li, Jiaoyang},
    journal={arXiv preprint arXiv:2511.21886},
    year={2025}
  }
citation: 'Jingtian Yan, Shuai Zhou, He Jiang, Stephen F. Smith, and Jiaoyang Li. <i>arXiv preprint arXiv:2511.21886</i>. 2025.'
---

## Overview

This work addresses the gap between theoretical multi-agent path planning and practical robotic deployment. It introduces ExecTimeNet, a learned world model of MAPF execution that predicts how a discrete MAPF solution will unfold on physical robots. Building on this model, the paper proposes REMAP, an execution-aware planning framework, and ESADG, a post-planning optimization method.

Results show up to 21% delay reduction in simulation across diverse scenarios and a 15.3% execution time improvement on physical hardware, demonstrating successful sim-to-real transfer for coordinating hundreds of agents in applications such as warehouse automation.

<div style="text-align: center;">
<img src="/images/exectimenet-overview.png" alt="ExecTimeNet overview" style="max-width: 100%; height: auto;">
<br><em>Figure 1: ExecTimeNet overview</em>
</div>
<br>

**Links:**
- [Paper (arXiv)](https://arxiv.org/abs/2511.21886)
- [Intro Overview (PDF)](/files/2026_ExecTimeNet/intro-overview-v1.pdf)

## BibTeX

```bibtex
@article{yan2025exectimenet,
  title={From Discrete Plans to Real-World Execution: A World-Model-Driven Framework for Execution-Aware Multi-Agent Path Finding},
  author={Yan, Jingtian and Zhou, Shuai and Jiang, He and Smith, Stephen F. and Li, Jiaoyang},
  journal={arXiv preprint arXiv:2511.21886},
  year={2025}
}
```
