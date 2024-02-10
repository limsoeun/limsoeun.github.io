---
layout: category
title: "라이브러리"
category: 라이브러리
permalink: /category/라이브러리/
---
<h1>{{ page.title }}</h1>

<ul>
  {% for post in site.posts %}
    {% if post.category == page.category %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>
