---
title: " "
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}


<!-- # Past research -->
<!--
{% include base_path %}

{% for post in site.pastresearch reversed %}
  {% include archive-single.html %}
{% endfor %} -->
