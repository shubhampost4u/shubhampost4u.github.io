---
layout: page
title: Welcome 
tagline: to Notes For Civil Service
---
{% include JB/setup %}
{% include welcome.html %}

###Blog Posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>





