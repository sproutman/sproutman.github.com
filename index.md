---
layout: page
title: ! Welcome !
#tagline: Supporting tagline
---
{% include JB/setup %}



    
## look my Posts

This blog contains some posts which help stage pages and blog data.


Here's the "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



