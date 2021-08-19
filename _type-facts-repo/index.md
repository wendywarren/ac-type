---
layout: subpage
serial: level-3-repo-4-home
--- 
<ul>
	{% for items in site.type-facts-repo %}
		{% if items.serial contains "subpage" %} 
			<li><a href="{{site.baseurl}}{{site.url}}{{ items.url }}">{{ items.title }}</a></li>
		{% endif %}
	{% endfor %} 
</ul>
