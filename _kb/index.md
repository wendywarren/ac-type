---
layout: type
type: home
title: Type Knowledge
---
<ul class="hasBullets columns3">
{% for kb_item in site.kb %}
	{% if kb_item.serial contains 'kb-subpage' %} 
	<li><a href="{{ kb_item.url }}" title="{{ kb_item.title }}">{{ kb_item.title }}</a></li>
	{% endif %}
{% endfor %}
</ul>