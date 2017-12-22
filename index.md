---
layout: default
title: Markville Robotics
---

## Hello!
Welcome to Markville Robotic's website!
What is Markville Robotics, you ask? Well, Markville Robotics is the robotics initiative at Markville Secondary School.

## Announcements
<ul>
  {% for post in site.categories.announcements %}
    <li>
      <a href="{{ post.url }}"> - {{ post.title }} - {{page.date}}
      </a><{{ post.summary }}
    </li>
  {% endfor %}
</ul>

###
