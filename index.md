---
layout: page
title: fotitud
tagline: the recipe to make me.
---
{% include JB/setup %}

First of all, I'm a super kawaii boy.

Then I major in Computer Science but my final destination is so damn further than just do computer.
    
## Blogs

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

More stuffs are on their way :P


