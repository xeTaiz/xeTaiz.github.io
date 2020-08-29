---
permalink: /
title: "About Me"
author: Dominik Engel
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi, I'm Dominik! I'm a PhD student at Ulm University, where I am part of the [Visual Computing Group](https://www.uni-ulm.de/en/in/mi/research-groups/viscom/), supervised by [Prof. Dr. Timo Ropinski](https://www.uni-ulm.de/en/in/mi/institute/staff/timo-ropinski/).
My main interest is deep learning on visual data. Currently I'm specifically interested in applying deep learning to volume rendering.

<br />
# Publications
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br />
# Open Source Projects
{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
