---
layout: category
title: "컴퓨터구조"
category: 컴퓨터구조
permalink: /category/컴퓨터구조/
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
