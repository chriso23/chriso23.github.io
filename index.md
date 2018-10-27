---
layout: default
title: Blog posts
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
      <p><small class="date"><time datetime="{{ post.date | date: "%b %-d, %Y" }}">{{ post.date | date_to_long_string }}</time></small></p>
    </li>
    <br/>
  {% endfor %}
</ul>
