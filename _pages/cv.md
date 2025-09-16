---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Academic positions
======
* Senior Research Fellow, UCL, 2024 --
* Research Fellow, UCL, 2022 -- 2024

Education
======
* Ph.D in economics, Sciences Po, 2022
* MRes in economics, Sciences Po, 2017
* AdvDip in economics, University of Cambridge, 2014
* BSc in mathematics and chemistry, University of Birmingham, 2012

Research
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Policy work
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
* Organiser of CEPEO seminar series
* Referee: Econ of Ed Review; Education Economics
