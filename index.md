---
layout: default
title: 1988 EV Suzuki Samurai
---

![samurai](https://github.com/rushtonmd/88evsamurai.github.io/assets/1479022/319f9aa9-977a-47f7-97fd-f53c5ce35dcc)
<img width="1427" alt="Screen Shot 2024-03-05 at 3 05 56 PM" src="https://github.com/rushtonmd/88evsamurai.github.io/assets/1479022/c40cb9d2-5b76-4cbc-ac51-8b8d99682391">
<img width="1427" alt="Screen Shot 2024-03-05 at 3 05 34 PM" src="https://github.com/rushtonmd/88evsamurai.github.io/assets/1479022/356e22ba-99a3-4f60-acd4-ddb8ac4a8926">
<img width="1427" alt="Screen Shot 2024-03-05 at 3 05 35 PM" src="https://github.com/user-attachments/assets/bd5317a5-58af-42f7-b453-d384ba9428f4">

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2>{{ post.date | date: '%B %d, %Y' }} - <a href="{{ post.url }}">{{ post.title }}</a></h2>
    </li>
  {% endfor %}
</ul>
