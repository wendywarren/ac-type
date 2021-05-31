---
layout: default
title: Typography 3
--- 

{% assign all_grids = site.grids %} 
<ul>
	{% for item in all_grids %} 
	<li><a href="{{site.url}}{{item.url}}" class="{% if undeterminedlevel.formsum == 'summative' %}summative{% endif %}">{{ item.title }}</a></li>
	{% endfor %}
</ul>

<ul>
{% assign pagetypes = site.documents | sort: 'sortorder' %}
{% for pagetype in pagetypes %}
		<li class="{% if pagetype.type == 'theory' %}pagetypetheory{% endif %}{% if pagetype.type != 'theory' %}pagetypeother{% endif %}"><a href="{{ site.baseurl }}{{pagetype.url}}" title="{{ pagetype.deck }}">{{ pagetype.title }}</a></li>
{% endfor %}
</ul>
