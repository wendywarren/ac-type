---
layout: type
type: home
title: Type Knowledge Base
---
<ul class="hasBullets columns3">
{% for kb_item in site.kb %}
	<li><a href="{{ site.url }}/{{ kb_item.url }}" title="kb_item.title">{{ kb_item.title }}</a></li>
{% endfor %}
</ul>