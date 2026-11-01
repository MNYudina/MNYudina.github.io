---
layout: archive
title: "博客文章"
permalink: /zh/year-archive/
author_profile: true
lang: zh
ref: year-archive
---

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% assign posts = site.posts | where: "lang", page.lang %}
{% for post in posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
