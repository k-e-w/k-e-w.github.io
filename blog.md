---
id: 367
title: Blog
date: 2010-07-30T03:01:19+00:00
author: Jonathan Eyler-Werve
layout: default
guid: http://www.eylerwerve.com/

redirect_from:
  - /2015/
  - /2014/
  - /2013/
  - /2012/
  - /2011/
  - /2010/
---


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>