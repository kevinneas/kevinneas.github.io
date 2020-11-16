---
title: "Archive"
layout: archive
permalink: /archive/
author_profile: true
---
{% for post in paginator.posts %}
  {% include archive-single-main.html %}
{% endfor %}

{% if page.url == '/' and insta_image != true and site.url == 'fake.url' %}
  <h1 class="archive__subtitle">Instagram Feed</h1>
  <div id="IG_bottom">
      <figure class="sixth" id="IG_bottomFigure"></figure>
  </div>
{% endif %}

{% include paginator.html %}