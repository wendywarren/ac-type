---
layout: subpage
serial: level-3-type-facts-repo-home
--- 
<ul>
	{% for items in site.type-facts-repo %}
		{% if items.serial contains "subpage" %} 
			<li><a href="{{site.baseurl}}{{ items.url }}">{{ items.title }}</a></li>
		{% endif %}
	{% endfor %} 
</ul>
