---
layout: default
title: Blog
---
<!---------Loops through all posts---------------->
<ul class="posts">
  {% for post in site.posts %}
  <li>
    <small class="date">{{ post.date | date: "%b %-d, %Y" }}</small><br/>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  <br/>
  {% endfor %}
</ul>
