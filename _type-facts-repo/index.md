---
layout: subpage
serial: level-3-type-facts-repo-home
---
<ul>
{% for items in site.type-facts-repo %}
	<li><a href="{{ items.url }}">{{ items.title }}</a></li>
{% endfor %}
</ul>