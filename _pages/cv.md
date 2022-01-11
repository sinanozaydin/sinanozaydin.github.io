---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A pdf form of the CV can be reached at from <a href="https://sinanozaydin.github.io/files/CV_Sinan_Ozaydin.pdf">HERE</a>.

Employment
======
* Postdoctoral Research Fellow, Macquarie University 2021-
* Research Associate, University of South Australia 2021-2022

Education
======
* PhD in Geophysics, Macquarie University, 2021
* MSc in Geophysics, Boğaziçi University, 2017
* BS in Geophysical Engineering, Istanbul Technical University, 2015

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Selected Talks (First Author Only)
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
