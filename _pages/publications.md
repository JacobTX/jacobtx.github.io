---
title: "Publications"
layout: single
permalink: /publications/
author_profile: true
---

{% assign items = site.publications | sort: "date" | reverse %}
{% for post in items %}
  {% include archive-single.html %}
{% endfor %}

---

*Author name appears as **Sony, Jacob T.** For the latest list, see my
[LinkedIn profile](https://www.linkedin.com/in/jacob-thomas-sony-8aa155214/).*
