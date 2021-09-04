---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
header:
  overlay_color : "#000"
  overlay_filter: "0.5"
  overlay_image: banner.png
  actions:
  caption: ""
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Preprints
======
{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

Published Works
======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
