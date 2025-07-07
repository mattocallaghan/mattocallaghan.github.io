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
* Ph.D in Astronomy and Data Intensive Sciences, University of Cambridge, 2025 (expected)
* Part III MASt in Mathematics, University of Cambridge, 2021
* B.A. in Mathematics, Trinity College, Dublin, 2020

Work experience
======
* 2024: Research Assistant
  * National Observatory of Athens
  * Atmospheric physics research on dust particle optical properties

* 2019 & 2020: Machine Learning Engineer
  * Eirgrid
  * Future electical demand forcasting


  

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
  
