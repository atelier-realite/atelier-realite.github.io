---
layout: default
---

<h1>アトリエリアリテのかつどう内容</h1>

<ul>
  <li>新宿ダンジョン</li>
  <li>VRずかん</li>
  <li>複数人VR</li>
</ul>

<hr>

{% for post in site.categories.repo %}
  <div>
    {{ post.date | date: "%Y.%m.%d" }} <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
  </div>
{% endfor %}
