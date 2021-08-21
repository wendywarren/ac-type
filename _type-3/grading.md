---
layout: default
serial: level-3-subpage-grading
---
### Course Description
<div>
	{% if page.serial contains 'level-3' %}
		{{ site.data.metadata.courses[0].course-description }}
	{% elsif page.serial contains 'level-4' %}
		{{ site.data.metadata.courses[1].course-description }}
	{% endif %}
</div>

### Grading
<ul>
{% for allValues in site.data.assignments %}
	{% if allValues.serial contains "level-3" %} 
	<li style="font-family: 'FiraSans-Medium'; margin-top: 1rem;">{{ allValues.title }}</li>
	<li style="font-family: 'FiraSans-MediumItalic'; font-size: 0.75rem;">Point Value: {{ allValues.point-value }}%</li>
	<li style="">{{ allValues.deck }}</li>
	{% endif %}
{% endfor %}
</ul>