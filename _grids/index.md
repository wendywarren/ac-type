---
layout: home
sortorder: 1.0
title: "Grids"
description: |
  Page layout grids create structure and harmony on the page.
resources: |
  - This is a really good example using formulas to [create grids](http://retinart.net/graphic-design/secret-law-of-page-harmony/)
  - [Good layout/grids info here](https://learning.oreilly.com/library/view/typography-referenced/9781592537020/chapter-49.html)
  - [About grids](https://learning.oreilly.com/library/view/the-art-of/9781315301532/xhtml/14_Chapter08.xhtml#ch8-5)
  - [Types of Grids](https://learning.oreilly.com/library/view/the-art-of/9781315301532/xhtml/14_Chapter08.xhtml#ch8)
---
In this module, we'll learn how to design page layout grids.

We're always told to create a grid to guide our page layouts. But where do we start? How do we decide how to divide the page? We'll use various formula to create harmonious grids.

Page layout grids can be thought of as imaginary lines that divide the page. They create a visual path from one element to the next, creating relationships and continuity between adjacent elements on the page.

{% assign all_pages = site.grids-pages | sort: 'sortorder' %} 
<ul>
	{% for atom in all_pages %} 
		<li><a href="{{ site.url }}{{ atom.url }}">{{ atom.title }}</a></li>
	{% endfor %} 
</ul>