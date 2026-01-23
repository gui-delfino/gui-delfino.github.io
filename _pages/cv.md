---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can find my complete CV [here](https://gui-delfino.github.io/files/delfino_CV.pdf)!


Education
======
* Ph.D in Physics, Purdue University, 2027 (expected)
* M.A. in Physics, Boston University, 2025
* B.S. with honors & M.S. in Physics, 2019

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
  
Academic Services
======
* Referee for SciPost, Physical Reviews, and JHEP
