---
layout: default
title: "Worlds"
permalink: /worlds
---

# Worlds
宇宙に関するVRChat worldをご紹介します。

{% assign tag_names = "" | split: "|"  %}

{% for posts_by_tag in site.tags %}
  {% assign tag_names = tag_names | push: posts_by_tag.first %}
{% endfor %}

{% assign tag_names = tag_names | sort %}

<hr>

<div>
  {% assign curDate = site.time | date: '%s' %}
  <ul>
    {% for post in site.tags["world"] %}
      {% assign postStartDate = post.date | date: '%s' %}
      {% if postStartDate < curDate %}
        <li>
          <a href="{{ post.url | relative_url }}">
            <div class="thumbnail">
              <h3>{{ post.title }}</h3>
              {{ post.excerpt }}
            </div>
          </a>
        </li>
      {% endif %}
    {% endfor %}
  </ul>
</div>
