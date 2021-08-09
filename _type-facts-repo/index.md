---
layout: subpage
serial: type-facts-repo-home
---
<ul>
{% for items in site.type-facts-repo %}
	<li>{{ items.title }}</li>
{% endfor %}
</ul>