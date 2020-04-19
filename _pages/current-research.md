---
title: "<h1>Current Research</h1>"
permalink: /current-research/
author_profile: true
redirect_from:
  - /current-research
---

{% include base_path %}

{% for post in site.current-research reversed %}
  {% include archive-single.html %}
{% endfor %}
