---
layout: default
serial: level-3-type-trivia-home
---
This is a list of all the type trivia items. We may just have a quiz based on these.

<ul class="columns3">
	{% for allItems in site.data.assignments %}
	{% for item in allItems.pages %}
		{% if item.serial contains "type-trivia" %} 
			<li><a href="{{site.url}}/{{ item.url }}">{{ item.title }}</a></li>
		{% endif %}
	{% endfor %}
	{% endfor %}
</ul>
