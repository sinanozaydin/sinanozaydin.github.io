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
Hello! I am a PhD candidate at Macquarie University. My research focuses on detailed interpretations of magnetotelluric models of the mantle. I do this by utilising the knowledge I acquired from 3D magnetotelluric modelling, experimental petrology and geochemical data.

Blog Posts
======

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

Latest Research
======
include archive-single.html site.preprints.safII.md
