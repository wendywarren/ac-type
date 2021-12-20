---
layout: type
type: Home
title: Typography 3 & 4
---
<h1>Home</h1>

<ul>
{% for posts in site.posts limit:5 %}
	<li class="post_title">{{ posts.title }}</li>
	<li class="post_excerpt">{{ posts.excerpt }}</li>
{% endfor %}
</ul>