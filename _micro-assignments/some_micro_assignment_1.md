---
layout: subpage
serial: level-3-micro-assignment-1-subpage
---
<ul>
{% for items in site.type-facts-repo %}
	<li>{{ items.title }}</li>
{% endfor %}
</ul>