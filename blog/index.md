---
layout: category
title: Blog
---
Please excuse the broken date formatting.
<ul>
  {% for post in site.categories.announcements %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }} - {{ post.date }} </a> <br> {{ post.summary }}
      <br><br>
    </li>
  {% endfor %}
</ul>
