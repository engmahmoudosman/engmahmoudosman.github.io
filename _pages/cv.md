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
* M.S. in Electronics Engineering, Joannem University of Applied Sciences, 2024 - present
* B.S. in Electrical Engineering, University of Pécs, 2023

Work experience
======
* Lecturer
  * University of Pécs

  
Skills
======
* Hardware Design
  * PCB design with Altium Designer
* Software Design
  * C++
  * Python
  * RTOS
* Laboratory Tools
  * Oscilloscope
  * Power Supply


  
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
  

