---
layout: default
title: Publications
---

{% for pub in site.publications reversed %}
  {% include archive-single.html pub=pub %}
{% endfor %}
