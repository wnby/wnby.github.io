---
layout: page
title: 论文精读
permalink: /papers/
---

这里记录我的论文阅读笔记与思考。

<ul class="post-list">
{% for post in site.categories.papers %}
  <li>
    <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span>
    <h2>
      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </h2>
  </li>
{% endfor %}
</ul>