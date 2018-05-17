---
layout: default
---

<h2>アトリエリアリテとは？</h2>
<ul>
  <li>VRに興味を持っているメンバーがもくもく創作活動する集団です</li>
  <li>活動状況などもお伝えしていきます</li>
  <li>現在リコーITソリューションズに所属するメンバーが主となり活動していますが、一緒にもくもくしたい方はぜひお声がけください</li>
</ul>
<hr>

{% include sns.html %}

<hr>
<div class="container-fluid">
  <div class="row">
    <div class="col">
      メンバー
      <ul>
        <li>yuri🍎</li>
        <li>chano2</li>
        <li>kana</li>
        <li>arahori</li>
        <li>ca7mi</li>
        <li>moe🎧</li>
        <li>sentomo</li>
        <li>nishii☔</li>
      </ul>
      <!--<h2>卒業生</h2>
      <ul>
        <li>まだいない</li>
      </ul>-->
    </div>
    <div class="col">
      応援団
      <ul>
        <li>確認中</li>
      </ul>
    </div>
    <div class="col">
      シショー
      <ul>
        <li>募集中</li>
      </ul>
    </div>
  </div>
</div><!-- container-fluid -->
<hr>

<h2>入部希望者向けリンク</h2>
準備中

<hr>

メンバーのつぶやき＞＞＞

{% for post in site.categories.repo %}
  <div>
    {{ post.date | date: "%Y.%m.%d" }} <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
  </div>
{% endfor %}
