---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Welcome to my portfolio. I am an Electrical Engineering student at the University of Oklahoma with experience in power systems, industrial controls, and aerospace avionics.

### Featured Projects
Below are some of my recent engineering projects. You can view the full details in the [Portfolio](/portfolio/) section.

{% for post in site.portfolio limit:3 %}
  {% include archive-single.html %}
{% endfor %}
