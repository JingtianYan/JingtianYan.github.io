---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Robotics**, Carnegie Mellon University, 2024-Present
  * Advisors: Prof. Jiaoyang Li and Prof. Stephen Smith
  * Focus: Multi-robot coordination, autonomous exploration, and multi-agent motion planning
* **M.S. in Electrical and Computer Engineering**, Carnegie Mellon University, 2021-2023
  * Focus: Multi-agent systems and autonomous exploration
* **B.S. in Automation**, Zhejiang University, 2017-2021
  * Focus: Control systems and robotics

Research Experience
======
* **2024-Present: Ph.D. Research Assistant**
  * Carnegie Mellon University, Robotics Institute
  * Research on multi-agent motion planning and coordination
  * Supervisors: Prof. Jiaoyang Li and Prof. Stephen Smith

* **2021-2023: Graduate Research Assistant**
  * Carnegie Mellon University, Robotics Institute
  * Research on cooperative multi-agent exploration with unknown initial positions

Research Interests
======
* Multi-Agent Motion Planning
* Multi-Robot Coordination  
* Autonomous Exploration
* Path Planning and Navigation
* Robotics and AI

Skills
======
* **Programming Languages**: Python, C++, MATLAB, ROS
* **Robotics Frameworks**: ROS, Gazebo, NVIDIA Isaac Sim
* **Machine Learning**: PyTorch, TensorFlow
* **Optimization**: Motion planning, trajectory optimization
* **Research**: Algorithm design, experimental validation, technical writing

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Reviewer for AAAI, IROS, ICRA, and RA-L.
