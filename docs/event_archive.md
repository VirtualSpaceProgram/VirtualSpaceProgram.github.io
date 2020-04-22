# イベントアーカイブ
VSPが過去に行ったイベント一覧です。

{% assign tag_names = "" | split: "|"  %}

{% for posts_by_tag in site.tags %}
  {% assign tag_names = tag_names | push: posts_by_tag.first %}
{% endfor %}

{% assign tag_names = tag_names | sort %}

<hr>

<div>
  {% assign curDate = site.time | date: '%s' %}
  <ul>
    {% for post in site.tags["event"] %}
      {% assign postStartDate = post.date | date: '%s' %}
      {% if postStartDate < curDate %}
        <li>
          <h3><a href="{{ post.url | relative_url }}">{{ post.date | date: '%Y/%m/%d' }}: {{ post.title }}</a></h3>
        </li>
      {% endif %}
    {% endfor %}
  </ul>
</div>
