---
permalink: /
title: "Sinan Özaydın"
excerpt: "About me"
author_profile: true
header:
  overlay_color : "#000"
  overlay_filter: "0.5"
  overlay_image: banner_about.jpeg
  actions:
  caption: ""
excerpt: "Earth Scientist"
redirect_from:
  - /about/
  - /about.html
---

About Me
======
Hello! I am an Earth scientist currently employed at University of Sydney as a postdoctoral research associate. My research targets how the electrical conductivity distribution of the lithosphere, as it is acquired from magnetotelluric models, can be related to tectonic and magmatic processes. I try to do this via quantified interpretations, combining the knowledge from geochemistry, petrology, magnetotellurics and thermomechanical modelling.

Blog Posts
======

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

Latest Research
======
{% for post in site.preprints %}
  {% include archive-single.html %}
{% endfor %}
