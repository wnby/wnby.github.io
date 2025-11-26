---
layout: page
title: 个人项目
permalink: /projects/
---

这里展示我个人开发的有趣项目。

<ul class="post-list">
{% for post in site.categories.projects %}
  <li>
    <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span>
    <h2>
      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </h2>
  </li>
{% endfor %}
</ul>