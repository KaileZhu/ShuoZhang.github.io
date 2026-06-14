---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div style="margin-bottom: 1.5em;">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary" style="text-decoration: none;">
    <i class="fas fa-download" aria-hidden="true"></i> Download CV (PDF)
  </a>
</div>

Education
======

<div style="display: flex; align-items: baseline; flex-wrap: wrap;">
  <strong>M.S. student</strong>
  <span style="margin-left: auto; white-space: nowrap;">2024 – 2027 (expected)</span>
</div>

College of Advanced Manufacturing and Robotics, **Peking University**

<div style="display: flex; align-items: baseline; flex-wrap: wrap; margin-top: 1.2em;">
  <strong>B.S. in Automation</strong>
  <span style="margin-left: auto; white-space: nowrap;">2020 – 2024</span>
</div>

College of Information Science and Engineering, **Northeastern University**

Research Experience
======

<div style="display: flex; align-items: baseline; flex-wrap: wrap;">
  <strong>Graduate Research Assistant</strong>
  <span style="margin-left: auto; white-space: nowrap;">Sep 2024 – present</span>
</div>

Multi-Agent Control and Decision (MAC&D) Laboratory, Peking University
- Research on large language models for robot task planning
- Advisor: Prof. Zhongkui Li

Skills
======

- **Programming:** Python, C++
- **Frameworks & Tools:** ROS, PyTorch, Git, Linux, LaTeX
- **Languages:** Chinese (native), English

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
