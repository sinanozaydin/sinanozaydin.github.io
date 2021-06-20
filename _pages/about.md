---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am a PhD candidate at Macquarie University. My research focuses on detailed interpretations of magnetotelluric models of the mantle. I do this by utilising knowledge I acquired from 3D magnetotelluric modelling, experimental petrology and geochemistry.

Blog Posts
======

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
