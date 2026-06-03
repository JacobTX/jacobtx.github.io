---
title: "Research"
layout: single
permalink: /research/
author_profile: true
---

My research spans **robotics and legged locomotion**, **structural and vibration
mechanics**, **biomedical rehabilitation**, and **energy systems** — carried out
through my Master's thesis at IIT Bombay and international research internships in
Canada and the USA.

{% assign items = site.research | sort: "order" %}
{% for post in items %}
  {% include archive-single.html %}
{% endfor %}
