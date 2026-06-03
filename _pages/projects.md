---
title: "Projects"
layout: single
permalink: /projects/
author_profile: true
---

A selection of course and technical projects across **solid &amp; fracture
mechanics**, **control and robotics**, **machine learning**, and **manufacturing** —
spanning analytical modeling, simulation, experimentation, and software.

{% assign items = site.projects | sort: "order" %}
{% for post in items %}
  {% include archive-single.html %}
{% endfor %}
