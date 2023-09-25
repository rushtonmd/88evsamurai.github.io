---
layout: default
title: 1988 EV Suzuki Samurai
---

![samurai](https://github.com/rushtonmd/88evsamurai.github.io/assets/1479022/319f9aa9-977a-47f7-97fd-f53c5ce35dcc)

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2>{{ post.date | date: '%B %d, %Y' }} - <a href="{{ post.url }}">{{ post.title }}</a></h2>
    </li>
  {% endfor %}
</ul>
