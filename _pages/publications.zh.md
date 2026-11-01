---
layout: archive
title: "论文"
permalink: /zh/publications/
author_profile: true
lang: zh
ref: publications
---

{% include base_path %}

{% assign posts = site.publications | where: "lang", page.lang %}
{% for post in posts reversed %}
  {% include archive-single.html %}
{% endfor %}
