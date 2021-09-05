---
layout: default
serial: level-3-subpage-grading
---
### Course Description

<table class="rubric">
	<thead>
	<tr>
	<th>Assignment</th>
	<th>Type</th>
	<th class="column-3">Weight</th>
	</tr>
	</thead>
	<tbody>
	<tr><td>Poster</td><td>File Submission</td><td class="column-3">20%</td></tr>
	<tr><td>Grimm Dust Cover</td><td>File Submission</td><td class="column-3">20%</td></tr>
	<tr><td>Grimm's Pages</td><td>File Submission</td><td class="column-3">20%</td></tr>
	<tr><td>Presentations</td><td>Presentations</td><td class="column-3">10%</td></tr>
	<tr><td>Quiz Pool</td><td>Lots'o'Quizzes</td><td class="column-3">10%</td></tr>
	</tbody>
</table>

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

