---
layout: default
title: "天文仮想研究所: Virtual Space Program"
---

# 天文仮想研究所 -VSP-

天文仮想研究所(Virtual Space Program: VSP)とは、VRchat内において天体、宇宙、星等に関するイベント、集会を行うグループです。

## [Discord](http://discord.gg/znwtKr4)
VSPはVRChatだけでなくDiscordでも交流が盛んです。是非ご参加ください。

## イベントカレンダー
開催予定のイベント一覧です。最新情報はDiscordをご覧ください。

<ul>
  {% assign curDate = site.time | date: '%s' %}
  {% assign sorted = site.posts | reverse %}
  {% for post in sorted %}
    {% assign postStartDate = post.date | date: '%s' %}
    {% if postStartDate >= curDate %}
      <li>
        <h3><a href="{{ post.url | relative_url }}">{{ post.date | date: '%Y/%m/%d' }}: {{ post.title }}</a></h3>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## [News](/news)
イベント情報や掲載情報をご紹介します。

<ul>
  {% assign curDate = site.time | date: '%s' %}
  {% for post in site.posts limit:10 %} 
    {% assign postStartDate = post.date | date: '%s' %}
    {% if postStartDate < curDate %}
      <li>
        <h3><a href="{{ post.url | relative_url }}">{{ post.date | date: '%Y/%m/%d' }}: {{ post.title }}</a></h3>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## [イベントアーカイブ](/docs/event_archive.md)
過去のイベント一覧です。

## [Worlds](/worlds)
宇宙に関するWorldをご紹介します。

## [Tags](/tags)
タグごとの記事一覧です。

## [編集者の方へ](/docs/how_to_contribute.md)
本ページの製作に関わっていただける方を大募集中です。
