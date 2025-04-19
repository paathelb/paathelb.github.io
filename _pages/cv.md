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
* MPhil in Computer Science and Engineering, The Hong Kong University of Science and Technology (HKUST), 2023
* B.S. in Applied Mathematics, University of the Philippines, 2019

Work experience
======
* Fall 2015: Research Assistant
  * HKUST
  * Duties included: workin on taxi profitability using machine learning and AI
  * Supervisor: Professor Hong Lo

* Spring 2024: Research Assistant
  * Hong Kong Polytechnic University
  * Duties includes: Updates and improvements to template
  * Supervisor: Prof. Guohao Shen

<!--
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3
-->

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
* Leader, Bridges International, Hong Kong Polytechnic University
