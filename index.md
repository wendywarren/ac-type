---
layout: type
type: Home
title: Home
---
<ul>
{% for posts in site.posts limit:5 %}
	<li class="post_title">{{ posts.title }}</li>
	<li class="post_excerpt">{{ posts.excerpt }}</li>
{% endfor %}
</ul>