---
layout: subpage
serial: level-3-type-trivia-home
--- 
<ul>
	{% for items in site.type-trivia %}
		{% if items.serial contains "subpage" %} 
			<li><a href="{{site.baseurl}}{{site.url}}{{ items.url }}">{{ items.title }}</a></li>
		{% endif %}
	{% endfor %} 
</ul>
