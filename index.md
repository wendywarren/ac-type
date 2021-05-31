---
layout: default
title: Typography 3
--- 

<ul>
{% assign pagetypes = site.documents | sort: 'sortorder' %}
{% for pagetype in pagetypes %}
		<li class="{% if pagetype.type == 'theory' %}pagetypetheory{% elsif pagetype.type != 'theory' %}pagetypeother{% endif %}"><a href="{{ site.baseurl }}{{pagetype.url}}" title="{{ pagetype.deck }}">{{ pagetype.title }}</a></li>
{% endfor %}
</ul>
