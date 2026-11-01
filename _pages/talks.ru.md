---
layout: archive
title: "Доклады и презентации"
permalink: /ru/talks/
author_profile: true
lang: ru
ref: talks
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/ru/talkmap.html">Посмотреть карту всех мест, где я выступала</a></p>

{% endif %}

{% assign posts = site.talks | where: "lang", page.lang %}
{% for post in posts reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
