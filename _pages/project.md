---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Here, you'll find a series of projects that I've been focusing on during my PhD! These projects will summarize the chapters of my dissertation (as I write them), while also highlighting the analytical methods I've learned over the course of my PhD.

---


{% include base_path %}

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}