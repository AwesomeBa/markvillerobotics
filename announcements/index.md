---
layout: category
title: Announcements
---
<ul>
  {% for post in site.categories.announcements %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }} - {{ post.date | date: '%B %d, %Y' }} </a> <br> {{ post.summary }}
      <br><br>
    </li>
  {% endfor %}
</ul>
