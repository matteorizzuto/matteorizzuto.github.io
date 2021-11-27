---
layout: archive
title: " "
permalink: /publications/
author_profile: true
---

  You can also find my articles on <u><a href="https://scholar.google.com/citations?user=V6rOyqgAAAAJ&hl">my Google Scholar profile</a></u> and <u><a href="https://www.researchgate.net/profile/Matteo-Rizzuto/research">my ResearchGate profile</a></u>.

{% include base_path %}

_In progress_

  {% for post in site.inprogress reversed %}
    {% include archive-single-pub.html %}
  {% endfor %}

<br>

{% include base_path %}

_Peer reviewed_

{% for post in site.publications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}
