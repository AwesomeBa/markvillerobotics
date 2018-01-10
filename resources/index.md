---
layout: category
title: Resources
---
<ul>
  {% for post in site.categories.resources %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }} </a> <br> {{ post.summary }}
      <br><br>
    </li>
  {% endfor %}
</ul>
