---
layout: default
serial: level-3-course-home
---
# Welcome to Type 3

### Course Description

Proficient typesetting allows a designer to compose and structure complex passages of content that are visually appealing in order to allow the information to be easily followed. Students combine text and imagery to craft professional layouts and informational documents.

### The Assignments

<ul>
{% for allValues in site.data.assignments %}
	{% if allValues.serial contains "level-3" %} 
	<li style="font-family: 'FiraSans-Medium'; margin-top: 1rem;">{{ allValues.title }}</li>
	<li style="font-family: 'FiraSans-MediumItalic'; font-size: .75rem;">Point Value: {{ allValues.point-value }}%</li>
	<li style="">{{ allValues.deck }}</li>
	{% endif %}
{% endfor %}
</ul>