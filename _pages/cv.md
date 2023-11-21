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
* Ph.D. in Theological Studies, University of Toronto, 2027 (expected)
* M.Div, Boston University, 2022
* B.S. in Philosophy and English, Brigham Young University, 2017

Theological Research
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Philosophy Research
======
  <ul>{% for post in site.philosophy %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
