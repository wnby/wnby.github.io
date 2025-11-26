---
layout: page
title: 摄影记录
permalink: /photography/
---

光影瞬间。

<div class="photography-list">
{% for post in site.categories.photography %}
  <div class="photo-post-item">
    <h3><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}
</div>