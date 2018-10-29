---
layout: page
title: Blog
---

<!---------Loops through all posts---------------->
<ul class="list-inline">
  {% for post in site.posts %}
  <li>
    <p><small class="date">{{ post.date | date: "%b %-d, %Y" }}</small></p>
  </li>
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  <br/>
  {% endfor %}
</ul>
