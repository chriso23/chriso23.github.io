---
layout: default
title: Blog
---

#### Blog posts
<br/>
<!---------Loops through all posts---------------->
<ul class="posts">
  {% for post in site.posts %}
    <li>
     <a href="{{ post.url }}">
        {{ post.title }}
      </a>
      <p><small class="date">Posted on {{ post.date | date: "%b %-d, %Y" }}</small></p>
    </li>
    <br/>
  {% endfor %}
</ul>
