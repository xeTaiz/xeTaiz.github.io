---
layout: archive
title: "CV"
permalink: /cv/
author: Dominik Engel
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Sc. in Computer Science, Ulm University, 2016
* M.Sc. in Media Informatics, Ulm University, 2018
* Ph.D in Computer Science, Ulm University, ongoing

Work experience
======
* 2013-2018 Daimler TSS GmbH: Working Student
  * Web Development (HTML, Angular), CI
  * Computer Vision
  * Bachelor Thesis: Visualization of robotic motion paths
  * Master Thesis: Deep-learning based 6D object detection

* 2018-now Ulm University: Research Associate


Skills
======
* Python: PyTorch, NumPy, matplotlib, multiprocessing, CuPy
* C++ 17
* Docker, Git

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Open Source Projects
======
  <ul>{% for post in site.projects %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
