---
layout: default
title: News
---
<h1>News</h1>

<ul>
  {% for post in site.posts %}
  <li>
    <h2><a href="{{ post.url | relative_url }}">{{ post.date | date: '%Y/%m/%d' }}: {{ post.title }}</a></h2>
  </li>
  {% endfor %}
</ul>
