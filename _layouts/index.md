---
layout: article
lang: ru-RU
title: Живопись для души
excerpt: Картины в доме - это не только радость и наслаждение от прекрасного, , но и вложение на будущее
---

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  {{ post.excerpt }}
{% endfor %}
