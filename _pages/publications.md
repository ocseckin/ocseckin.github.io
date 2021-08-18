---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My main research focuses on the "academic support networks". We investigate the thesis journey of PhD. students by extracting information from 27 thousand theses collected from pqdtopen.com (which is manually scraped from the website by a webscraping algorithm coded by me). The paper aims to inspect who is acknowledged, who is not, and how are they acknowledged using state of the art natural language processing tools that allow making large-scale research. We examine how the support providing entities are connected to each other by running network analysis and study gender based and disciplinary differences.

![Foto](ocseckin.github.io/images/ocs.jpg)


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
