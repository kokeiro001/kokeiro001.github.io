---
layout: page
title: コケいろの雑記。
---
{% include JB/setup %}


## このブログについて

雑記。

適当につらつら書いていく。



## 記事

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
