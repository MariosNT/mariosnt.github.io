---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
paperurl: 'http://academicpages.github.io/files/Marios_Kalomenopoulos_CV.pdf'
---

{% include base_path %}

Education
======
* Ph.D in Gravitational Waves Astrophysics and Cosmology, University of Edinburgh, 2018-2023
* M.Sc. in Theoretical Physics, University of Edinburgh, 2016-2017
* B.Sc. in Physics, National and Kapodistrian University of Athens, 2015

Work experience
======

- Postdoctoral Researcher, Multimessenger Astrophysics with emphasis on GWs, University of Nevada, Las Vegas, 2023-

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
