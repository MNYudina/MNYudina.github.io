---
layout: archive
title: "Преподавание"
permalink: /ru/teaching/
author_profile: true
lang: ru
ref: teaching
---

{% include base_path %}

{% assign posts = site.teaching | where: "lang", page.lang %}
{% for post in posts reversed %}
  {% include archive-single.html %}
{% endfor %}
