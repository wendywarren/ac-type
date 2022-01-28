---
layout: type4
serial: level-4-item-1-subpage-1
---
### Build a Modular Grid

Let's start to build our page grids from scratch. This is our starting information:

<ul class="hasBullets">
	<li>Letter sized pages - 612pt x 792pt</li>
	<li>12 point leading</li>
	<li>increased margins at the bottom for folios</li>
</ul>

Work in points since the type measurements are in points. In this specific case, **everything we measure will be divisible by at least 3, 4, 6, or 12.** A letter page measures 612 points wide by 792 points tall. 792 is divisible by: ... 6, 8, 9, 11, 12, 18, 22, 24, 33, 36, 44, 66, 72.

Let's create our modular grid. First, we'll go to `Layout > Margins & Columns…`. Set margins to:

| Margins  |   |   | 
|---|---|---|---|
| Top  | 60pt  | Inside  | 60pt  |
| Bottom  | 72pt  | Outside  | 60pt  |

Now, let's create a new layer named `Layout Grids`. Move to your parent pages. Let's aim to create a square grid module. We'll use our 72pt value from the bottom margin as a starting point.

On the new layer, let's use `Layout > Create Guides…` starting with 12pt gutters. From here, increase the numbers of columns and rows until they match our 72pt square. That gives us:

| Rows  |   | Columns  |    |
|---|---|---|---|
| Number  | 8  | Number  | 12pt  |
| Gutter  | 12pt  | Gutter  | 12pt  |

Now we have a modular grid which will easily accommodate text and graphics. We're ready to set up and work with our baseline grid.

### Why a Baseline Grid?

Aligning text to the baseline grid creates a structured and clean look with a rhythm on the page.

![Baseline Grids]({{site.url}}/svg/baseline-grids.svg){:width="90%"}

Working on a baseline grid can be tricky because the text sticks to the grid as you move it on the page. It makes things jump in increments, which is jarring. We'll get a handle on this with this assignment.

> Keep in mind that the baseline grid settings override the leading settings.

### The Settings

While working in InDesign, you should have guides turned on, `⌘ ;`. If you're aligning to the baseline grid, it stands to reason you should turn it on, `⌘ '` so you can see it.

It's best to first change some baseline grid settings. Hit `⌘-k`. Go to `Grids`. Start the grids at zero relative to the `Top Margin`. Make sure `Increment Every` is set to 12pt.

> There are two steps to using the baseline grid. The first is to establish the grid increment. The second is to align your text to the grid.

### Basic Baseline Alignment

Aligning simple columns of text to the baseline is not difficult. Set your type to the desired size and leading. Note your leading value. Go to `Preferences > Grids` to set your increment setting to the leading value.

The second step is to lock your text to the baseline. To do so, access the paragraph style settings. Go to `Indents & Spacing` to set the grid alignment to `All Lines`. This is the result.

![Baseline Grids]({{site.url}}/svg/baseline-grids.svg){:width="90%"}

### Varied Leading

Things get a little more challenging when there are titles interspersed in the text. Here, we need to plan for spacing before the titles.

![Using baseline grids with varied leading]({{site.url}}/svg/baseline-grids-varied-leading.svg){:width="90%"}

### Custom Baseline Grids

It's possible to set a custom baseline grid for a single text frame. This is ideal for a sidebar story. The settings are in `Object > Text Frame Options > Baseline Options`. You'll want to maintain the rhythm of the page, so use a value that fits with the rest of the page.

### Cap Height Grids

A problem often occurs when tops of photos don't align with the top of the text. To solve this, we'll create a cap height grid with which we'll align our photos.

![Line up photos with the cap height]({{site.url}}/svg/baseline-grids-cap-height.svg){:width="90%"}

In figure 1, you see the unwanted space in the orange hatched space. In figure number 2, you see the cap line grid. The photos have been moved to align with it.

### Persuasive Baseline Grids

This is an elegant, more relaxed way to align text to our baseline without actually locking it to the baseline grid. The strategy here is to have the leading for each piece of text have a common denominator. That means all your leading values should be divisible by the same number.

In the end, we don't need to align all our text to the baseline grid. If we align only the first lines, then use leading values that are factors of a common number, everything will look like it's aligned. I call this *persuasive baseline alignment*, rather than *forced baseline alignment*.

When we're working with different size text in neighbouring columns, We can also choose to align only the first line to the baseline grid. In that case, we should try to make the leading factors of a single number.