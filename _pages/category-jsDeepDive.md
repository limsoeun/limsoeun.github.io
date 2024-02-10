---
layout: category
title: "Javascript_DeepDive"
category: jsDeepDive
permalink: /category/jsDeepDive/
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
