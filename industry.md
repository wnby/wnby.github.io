---
layout: page
title: 横向项目
permalink: /industry/
---

参与的企业合作与横向课题记录。

<ul class="post-list">
{% for post in site.categories.industry %}
  <li>
    <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span>
    <h2>
      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </h2>
  </li>
{% endfor %}
</ul>