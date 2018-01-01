---
layout: category
title: Lessons
---
Please excuse the broken date formatting.
<ul>
  {% for post in site.categories.lessons %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }} - {{ post.date }} </a> <br> {{ post.summary }}
      <br><br>
    </li>
  {% endfor %}
</ul>
