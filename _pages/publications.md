---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
lang: en
ref: publications
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign posts = site.publications | where: "lang", page.lang %}
{% for post in posts reversed %}
  {% include archive-single.html %}
{% endfor %}
