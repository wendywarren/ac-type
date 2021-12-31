---
layout: type4
serial: level-4-item-1-subpage-1
---
{% include /svg/baseline-grid.svg %}

Create a type system that has a baseline grid that's all in multiples so it can accomodate body copy and sizes of titles.

We'll build a single-page layout with two stories which will be side-by-site. Each type element will be aligned to the baseline grid.

Make the text area divisible by the baseline grid, so the grid fits perfectly in the text area.

Baseline grid increments take precedence over the leading value.

A letter page measures 612 points wide by 792 points tall. 792 is divisible by: ... 6, 8, 9, 11, 12, 18, 22, 24, 33, 36, 44, 66, 72 ...

Make a baseline grid that's divisible into each type element's leading.

These are all multiple of 3 points, so everything lines up on the baseline grid.

When we're working with different size text in neighbouring columns, We can also choose to align only the first line to the baseline grid. In that case, we should try to make the leading factors of a single number.

- Leading of 13.5 x 2 = 27pt
- Leading of 9 x 3 = 27pt
- Every third line of 9pt type will line up with the bigger text.

Some circumstances demand that we halve the baseline grid to accommodate spacing before and/or after paragraphs.

We can have a custom baseline grid for a specific text frame. That's editable in the ⌘-b dialogue. Don't do this too much because it undermines the rhythm of your document.

In the end, we don't need to align all our text to the baseline grid. If we align only the first lines, then use leading values that are factors of a common number, everything will look like it's aligned. I call this *persuasive baseline alignment*, rather than *forced baseline alignment*.