---
layout: archive
title: "Lecture 1"
permalink: /lecture1/
author_profile: true
---

{% include base_path %}

{% for post in site.lecture1 reversed %}
  {% include archive-single.html %}
{% endfor %}
