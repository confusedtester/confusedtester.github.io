---
layout: page
title: Linux
permalink: /linux/
published: true
---
Linux for a Tester


<div class="posts">
  {% for post in site.tags.linux %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
