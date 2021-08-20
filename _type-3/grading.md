---
layout: subpage
serial: level-3-subpage-grading
---
# Grading
<ul>
{% for allValues in site.data.assignments %}
	{% if allValues.serial contains "level-3" %} 
	<li style="font-family: 'FiraSans-Medium'; font-size: 1.25rem; margin-top: 1rem;">{{ allValues.title }}</li>
	<li style="font-family: 'FiraSans-MediumItalic';">Point Value: {{ allValues.point-value }}%</li>
	<li style="">{{ allValues.deck }}</li>
	{% endif %}
{% endfor %}
</ul>