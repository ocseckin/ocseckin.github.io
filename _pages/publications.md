---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


You can also find my articles on Google Scholar.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
