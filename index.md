---
layout: page
title: Blog posts
---

### Blog posts
---

<!---------Loops through all posts---------------->
<ul class="posts">
  {% for post in site.posts %}
    <li>
     <a href="{{ post.url }}">
        {{ post.title }}
      </a>
      <p><small class="date">Published on {{ post.date | date: "%b %-d, %Y" }}</small></p>
    </li>
    <br/>
  {% endfor %}
</ul>
