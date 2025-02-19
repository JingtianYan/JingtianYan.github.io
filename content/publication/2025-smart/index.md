---
title: "Advancing MAPF towards the Real World: A Scalable Multi-Agent Realistic Testbed"
authors:
- admin
- Zhifei Li
- William Kang
- Yulun Zhang
- Stephen Smith
- Jiaoyang Li

date: "2025-03-01T00:00:00Z"
doi: "https://doi.org/10.1109/LRA.2024.3363543"

publishDate: "2025-02-01T00:00:00Z"

# publication_types: ["paper-conference"]

# publication: "*AAAI Conference on Artificial Intelligence*"
# publication_short: "(AAAI)"

# abstract: Multi-Agent Motion Planning (MAMP) seeks collision-free, dynamically feasible trajectories for multiple agents while minimizing travel time. Our proposed PSB method fully considers these constraints and generates smooth speed profiles for better execution.

# summary: Multi-Agent Motion Planning (MAMP) seeks collision-free, dynamically feasible trajectories for multiple agents while minimizing travel time.

tags:
- Multi-Agent Motion Planning
# - Bezier Curve Optimization
featured: false

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'
# url_pdf: "https://arxiv.org/abs/2412.13359"
# url_code: "https://github.com/JingtianYan/MASS-AAAI"
# url_video: ""

# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"
#   focal_point: ""
#   preview_only: false

# projects: []

# slides: "example"
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

<!-- <div style="display: flex; justify-content: center; gap: 20px;">
    <img src="mapf_def.gif" width="200" height="200" alt="GIF 1">
    <img src="two-agents.gif" width="200" height="200" alt="GIF 2">
    <img src="warehouse.gif" width="200" height="200" alt="GIF 3">
</div> -->

<div style="display: flex; justify-content: center; gap: 20px;">
    <img src="mapf_def.gif" style="height: 200px; width: auto;" alt="GIF 1">
    <img src="two-agents.gif" style="height: 200px; width: auto;" alt="GIF 2">
    <img src="warehouse.gif" style="height: 200px; width: auto;" alt="GIF 3">
</div>

#### Overview

<p class="small-text">We present Scalable Multi-Agent Realistic Testbed (SMART), a realistic and efficient software tool for evaluating Multi-Agent Path Finding (MAPF) algorithms coupling with robot models of different kinodynamics. MAPF focuses on planning collision-free paths for a group of robots. While state-of-the-art MAPF algorithms can plan paths for hundreds of robots in seconds, they often rely on simplified robot models, making their real-world performance unclear. Researchers typically lack access to hundreds of physical robots in laboratory settings to evaluate the algorithms. Meanwhile, industrial professionals who lack expertise in MAPF require a simulator to efficiently test and understand the performance of state-of-the-art MAPF algorithms. SMART fills this gap with several advantages: (1) SMART uses a physics-engine-based simulator to create realistic simulation environments, accounting for complex real-world factors such as robot kinodynamics and movement delays, (2) SMART uses an execution monitor framework based on the Action Dependency Graph, facilitating seamless integration with various MAPF algorithms and robot models, and (3) SMART scales to thousands of robots. In addition, we use SMART to explore and demonstrate research questions about the execution of MAPF algorithms in real-world scenarios.</p>

<!-- <p class="font-bold">This is large text.</p>
<p class="small-text">This is small text.</p>
This is default text -->