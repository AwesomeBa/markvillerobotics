---
layout: default
title: Markville Robotics
---

## Hello!
Welcome to Markville Robotics' website!
What is Markville Robotics, you ask? Well, Markville Robotics is the robotics initiative at Markville Secondary School.

## Announcements
Please excuse the broken date formatting.
<ul>
  {% for post in site.categories.announcements %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }} - {{ post.date }} </a> <br> {{ post.summary }}
      <br>
    </li>
  {% endfor %}
</ul>

## Lessons
<ul>
   {% for post in site.categories.lessons %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }} </a> <br> {{ post.summary }}
      <br>
    </li>
  {% endfor %}
</ul>

## Resources
<ul>
  {% for post in site.categories.resources %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }} - {{ post.date }} </a> <br> {{ post.summary }}
      <br>
    </li>
  {% endfor %}
</ul>
