---
layout: page
title: "Blog"
permalink: /blog/
---

Here are my posts about interesting topics and ideas.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>  
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>