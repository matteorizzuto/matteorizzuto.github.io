---
title: "<h1>Past Research</h1>"
permalink: /research/past-research/
author_profile: true
redirect_from:
  - /research/past-research
---

{% include base_path %}

{% for post in site.pastresearch reversed %}
  {% include archive-single.html %}
{% endfor %}
