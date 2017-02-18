---
layout: page
title: News & Notes
---
{% for post in site.posts %}
<div class="post">
  <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
  <p><strong>{{ post.date | date: "%B %e, %Y" }}</strong></p>
  {{ post.content }}
</div>
{% endfor %}
