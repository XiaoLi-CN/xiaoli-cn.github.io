---
layout: archive
permalink: /markdown/
title: "Posts"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

<!-- <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2> -->