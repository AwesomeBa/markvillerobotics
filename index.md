---
layout: home
title: Markville Robotics
---

## Hello!
Welcome to Markville Robotics' website! What is Markville Robotics, you ask? Well, Markville Robotics is the robotics initiative at Markville Secondary School. We are a student-led organization that provides opportunities for students in the school interested in developing skills around robotics and Computer Engineering. 

## [Sponsorship Information](https://markvillerobotics.github.io/sponsorship/)
We need your support!

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

<iframe src="https://calendar.google.com/calendar/b/2/embed?showTitle=0&amp;showPrint=0&amp;showTabs=0&amp;showCalendars=0&amp;showTz=0&amp;height=600&amp;wkst=1&amp;bgcolor=%23ffffff&amp;src=markvillerobotics%40gmail.com&amp;color=%23333333&amp;ctz=America%2FToronto" style="border-width:0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
