---
layout: default
title: "Home"
---


{% if site.show_excerpts %}
  {% include about.md %}
  {% include home.html %}
{% else %}
  {% include about.md %}
  {% include archive.html title="Posts" %}
{% endif %}
