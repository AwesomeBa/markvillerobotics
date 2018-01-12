---
layout: home
title: Markville Robotics
---

## Hello!
Welcome to Markville Robotics' website! What is Markville Robotics, you ask? Well, Markville Robotics is the robotics initiative at Markville Secondary School. We are a student-led organization that provides opportunities for students in the school interested in developing skills around robotics and Computer Engineering. 

## Description (temp)
Markville Robotics is the robotics initiative at Markville Secondary School. We are a student-led organization within that provides opportunities for students in the school interested in developing skills around robotics and Computer Engineering. 

## [Announcements](https://markvillerobotics.github.io/announcements/)
<ul>
  {% for post in site.categories.announcements %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }} - {{ post.date | date: "%Y-%m-%d" }} </a> <br> {{ post.summary }}
      <br><br>
    </li>
  {% endfor %}
</ul>

## [Lessons](https://markvillerobotics.github.io/lessons/)
<ul>
   {% for post in site.categories.lessons %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }} </a> <br> {{ post.summary }}
      <br><br>
    </li>
  {% endfor %}
</ul>

## [Resources](https://markvillerobotics.github.io/resources/)
<ul>
  {% for post in site.categories.resources %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }} </a> <br> {{ post.summary }}
      <br><br>
    </li>
  {% endfor %}
</ul>
