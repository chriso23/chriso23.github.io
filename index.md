---
layout: default
title: Blog
---

<!---------Loops through all posts---------------->
<ul class="posts">
  {% for post in site.posts %}
  <li>
    <div class="row">
      <div class="col-md-3">
      <small class="date">Posted: {{ post.date | date: "%b %-d, %Y" }}</small>
      </div> 
      <div class="col-md-9">
      <a href="{{ post.url }}">{{ post.title }}</a>
      </div>
    </div>
  </li>
  <br/>
  {% endfor %}
</ul>
