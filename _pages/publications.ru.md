---
layout: archive
title: "Публикации"
permalink: /ru/publications/
author_profile: true
lang: ru
ref: publications
---

{% include base_path %}

{% assign posts = site.publications | where: "lang", page.lang %}
{% for post in posts reversed %}
  {% include archive-single.html %}
{% endfor %}
