---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
lang: en
ref: teaching
---

{% include base_path %}

{% assign posts = site.teaching | where: "lang", page.lang %}
{% for post in posts reversed %}
  {% include archive-single.html %}
{% endfor %}
