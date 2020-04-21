# Virtual Space Program

Virtual Space Program(VSP)とは、VRchat内において天体、宇宙、星等に関するイベント、集会を行うグループです。

## [Discord](http://discord.gg/znwtKr4)
VSPはVRChatだけでなくDiscordでも交流が盛んです。是非ご参加ください。

## [News](./news.md)
イベント情報や掲載情報をご紹介します。

<ul>
	{% for post in site.posts limit:5 %} 
  <li>
    <h3><a href="{{ post.url | relative_url }}">{{ post.date | date: '%Y/%m/%d' }}: {{ post.title }}</a></h3>
  </li>
  {% endfor %}
</ul>

## [イベントアーカイブ](/docs/event_archive.md)
過去のイベント一覧です。

## [Tags](/tags)
タグごとの記事一覧です。

## [編集者の方へ](/docs/how_to_contribute.md)
本ページの製作に関わっていただける方を大募集中です。
