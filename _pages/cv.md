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
* Ph.D in Condensed Matter Theory, HKUST, 2025~present
* B.S. in Physics, Chongqing University, 2021~2025

Internship experience
======
* Summer 2024: 
  * IHEP, CAS
  * Learning includes: DAC
  * Supervisor: Xiaodong, Li

* Summer 2023: 
  * IOP, CAS
  * Learning included: TDAP
  * Supervisor: Sheng, Meng

* Summer 2023: 
  * USTC
  * Learning included: Hefei-NAMD
  * Supervisor: Qijing, ZHENG

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
