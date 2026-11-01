---
layout: archive
title: "报告与演示"
permalink: /zh/talks/
author_profile: true
lang: zh
ref: talks
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/zh/talkmap.html">查看我做过报告的所有地点的地图</a></p>

{% endif %}

{% assign posts = site.talks | where: "lang", page.lang %}
{% for post in posts reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
