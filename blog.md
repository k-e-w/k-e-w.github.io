---
id: 367
title: Blog
date: 2010-07-30T03:01:19+00:00
author: Jonathan Eyler-Werve
layout: default
guid: http://www.eylerwerve.com/
---


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>