---
title: "Operating System"
layout: archive
permalink: /categories/os
author_profile: true
sidebar_main: true
header:
  overlay_image : /assets/images/category/os.jpg
---

{% assign posts = site.categories.os | sort:"date" %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
