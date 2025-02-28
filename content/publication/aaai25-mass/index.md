---
title: "Multi-agent Motion Planning for Differential Drive Robots Through Stationary State Search"
authors:
- admin
- Jiaoyang Li

date: "2025-03-01T00:00:00Z"
doi: "https://doi.org/10.1109/LRA.2024.3363543"

publishDate: "2025-02-01T00:00:00Z"

publication_types: ["paper-conference"]

publication: "*AAAI Conference on Artificial Intelligence*"
publication_short: "(AAAI)"

abstract: Multi-Agent Motion Planning (MAMP) finds various applications in fields such as traffic management, airport operations, and warehouse automation. In many of these environments, differential drive robots are commonly used. These robots have a kinodynamic model that allows only in-place rotation and movement along their current orientation, subject to speed and acceleration limits. However, existing Multi-Agent Path Finding (MAPF)-based methods often use simplified models for robot kinodynamics, which limits their practicality and realism. In this paper, we introduce a three-level framework called MASS to address these challenges. MASS combines MAPF-based methods with our proposed stationary state search planner to generate high-quality kinodynamically-feasible plans. We further extend MASS using an adaptive window mechanism to address the lifelong MAMP problem. Empirically, we tested our methods on the single-shot grid map domain and the lifelong warehouse domain. Our method shows up to 400% improvements in terms of throughput compared to existing methods.

# summary: Multi-Agent Motion Planning (MAMP) seeks collision-free, dynamically feasible trajectories for multiple agents while minimizing travel time.

tags:
- Multi-Agent Motion Planning
# - Bezier Curve Optimization
featured: false

url_pdf: "https://arxiv.org/abs/2412.13359"
url_code: "https://github.com/JingtianYan/MASS-AAAI"
url_video: ""

# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"
#   focal_point: ""
#   preview_only: false

projects: []

# slides: "example"
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
#### Motivation
How to improve the solution quality of the MAMP in realistic cases?

<div style="display: flex; justify-content: center; gap: 20px;">
    <img src="intro.png" style="height: 300px; width: auto;" alt="GIF 1">
    <img src="intro.gif" style="height: 300px; width: auto;" alt="GIF 2">
    <!-- <img src="warehouse.gif" style="height: 200px; width: auto;" alt="GIF 3"> -->
</div>

### <span style="color: purple; font-weight: bold;">MASS (MAPF-SSIPP-SPS)</span>

<div style="text-align: center;">
    <img src="method_overview.png" alt="MASS Overview" style="width: 100%;">
</div>

---

### <span style="color: purple; font-weight: bold;">Stationary SIPP: Rotation Expansion</span>

<div style="display: flex; align-items: center; justify-content: center; gap: 20px;">
    <div style="flex: 1; text-align: center;">
        <img src="rotate_expansion.png" alt="Rotation Expansion" style="width: 90%;">
    </div>
    <div style="flex: 1;">
        <ul>
            <li>If the previous action is move, the next action must be rotation.</li>
            <li>During node expansion, generate the neighbor nodes by performing all possible rotations.</li>
        </ul>
    </div>
</div>

---

### <span style="color: purple; font-weight: bold;">Stationary SIPP: Movement Expansion</span>

<div style="text-align: center;">
    <img src="interval_search-v5.png" alt="Movement Expansion" style="width: 86%;">
</div>

<ul>
    <li>Find the stationary states in the current direction of the agent.</li>
    <li>Call the SPS to find a speed profile for a movement action. Generate a neighbor if one exists.</li>
</ul>


#### Results
Tested on MovingAI standard MAPF benchmark.
<div style="display: flex; justify-content: center; gap: 20px;">
    <img src="results.png" style="height: 300px; width: auto;" alt="GIF 1">
    <!-- <img src="intro.gif" style="height: 300px; width: auto;" alt="GIF 2"> -->
    <!-- <img src="warehouse.gif" style="height: 200px; width: auto;" alt="GIF 3"> -->
</div>
