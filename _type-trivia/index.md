---
layout: subpage
serial: level-3-type-trivia-home
--- 
This is a list of all the type trivia items. We may just have a quiz based on these.

<ul class="columns3">
	{% for items in site.type-trivia %}
		{% if items.serial contains "subpage" %} 
			<li><a href="{{site.baseurl}}{{site.url}}{{ items.url }}">{{ items.title | replace: ' ', '&nbsp;' }}</a></li>
		{% endif %}
	{% endfor %} 
</ul>