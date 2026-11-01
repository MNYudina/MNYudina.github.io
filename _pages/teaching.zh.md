---
layout: archive
title: "教学"
permalink: /zh/teaching/
author_profile: true
lang: zh
ref: teaching
---

{% include base_path %}

{% assign posts = site.teaching | where: "lang", page.lang %}
{% for post in posts reversed %}
  {% include archive-single.html %}
{% endfor %}
