---
layout: default
title: Latest Posts
---

<!---------Loops through all posts---------------->
<ul class="posts">
  {% for post in site.posts %}
  <li>
    <div class="row">
      <div class="col-sm-3 col-md-3 col-lg-3">
      <p class="date">Posted: {{ post.date | date: "%b %-d, %Y" }}</p>
      </div> 
      <div class="col-sm-9 col-md-9 col-lg-9">
      <a href="{{ post.url }}">{{ post.title }}</a>
      </div>
    </div>
  </li>
  <hr/>
  {% endfor %}
</ul>
