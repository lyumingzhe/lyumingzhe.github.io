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
* B.S. in Geophysics, Wuhan University, 2020
* M.S. in Geophysics, Southern University of Science and Technology, 2023
  
Research Area
======
* Three-dimensional deformation estimation
* Joint inversion of earthquake rupture process
* Tsunami modelling

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Presentations
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  