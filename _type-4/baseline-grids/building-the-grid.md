---
layout: type4
serial: level-4-item-1-subpage-1
---
Working on a baseline grid can be tricky because the text sticks to the grid as you move it on the page. It makes things jump in increments, which is jarring. We'll get a handle on this with this assignment.

Before we begin building our grid, it's important to understand that this whole process will be based on leading, and not text size. The reason for this is that the measurement of leading is taken from one baseline to the next. We begin by choosing our type size, then the leading that suits that text size.

We need to establish margins and the dimensions of the text area. We'll make it that the height of our text area is divisible by our chosen leading value.

[![Download Formative Assets]({{site.url}}/svg/button-download.svg){:width="40%"}](https://www.dropbox.com/s/fo8frdz34twiyxl/Baseline-Grids-Formative.zip?dl=1){:target="_blank"}

### The Settings

While working in InDesign, you should have guides turned on, `⌘ ;`. If you're aligning to the baseline grid, it stands to reason you should turn it on, `⌘ '` so you can see it.

> Keep in mind that the baseline grid settings override the leading settings.

It's best to first change some baseline grid settings. Hit `⌘-k`. Go to `Grids`. Start the grids at zero relative to the `Top Margin`. Make sure `Increment Every` is set to 12pt.

> There are two steps to using the baseline grid. The first is to establish the grid increment. The second is to align your text to the grid.

### Build a Modular Grid

Let's start to build our page grids from scratch. The following is our starting information, though this will change by project.

<ul class="hasBullets">
	<li>Letter sized pages - 612pt x 792pt</li>
	<li>12 point leading</li>
	<li>increased margins at the bottom for folios</li>
</ul>

> You need to start your project with your type selection and hierarchy established. You'll build your page grid based on this information (and maybe tweak it while building your grid).

Work in points since the type measurements are in points. A letter page measures 792 points tall. 792 is divisible by: ... 6, 8, 9, 11, 12, 18, 22, 24, 33, 36, 44, 66, 72. You can use [this factoring calculator](https://www.calculatorsoup.com/calculators/math/factors.php){:target="_blank"} to get divisors of any given number. These numbers are called *factors*, or *divisors*. This gives us numbers to work with for our leading at different type sizes.

![Baseline Grids - Our Page]({{site.url}}/svg/baseline-grids-our-page.svg){:width="60%"}

Let's create our modular grid on a Parent Page. First, we'll go to `Layout > Margins & Columns…`. Set margins to:

| Margins  |   |   | 
|---|---|---|---|
| Top  | 60pt  | Inside  | 60pt  |
| Bottom  | 72pt  | Outside  | 60pt  |

This leaves a content area that measures 660pt tall. This is divisible by 10, 11, 12, 15, 20, 22, 30, 33, 44, 55, 60, 66. Those are both good numbers for leading.

> You should always create margins which measure multiples of your base leading, or a divisor of it.

Now, let's create a new layer named `Layout Grids`. Move to your parent pages. Let's aim to create a square grid module. We'll use our 72pt value from the bottom margin as a starting point.

On the new layer, let's use `Layout > Create Guides…` starting with 12pt gutters. From here, increase the numbers of columns and rows until they match our 72pt square. That gives us:

| Rows  |   | Columns  |    |
|---|---|---|---|
| Number  | 8  | Number  | 6  |
| Gutter  | 12pt  | Gutter  | 12pt  |

Now we have a modular grid which will easily accommodate text and graphics. We're ready to set up and work with our baseline grid.

### Basic Baseline Alignment

Aligning simple columns of text to the baseline is not difficult. Set your type to the desired size and leading. Note your leading value. Go to `Preferences > Grids` to set your increment setting to the leading value.

The second step is to lock your text to the baseline. To do so, access the paragraph style settings. Go to `Indents & Spacing` to set the grid alignment to `All Lines`. This is the result.

![Baseline Grids]({{site.url}}/svg/baseline-grids.svg){:width="90%"}

### Varied Leading

Things get a little more challenging when there are titles interspersed in the text. Here, we need to plan for spacing before the titles.

![Using baseline grids with varied leading]({{site.url}}/svg/baseline-grids-varied-leading.svg){:width="90%"}

### Custom Baseline Grids

It's possible to set a custom baseline grid for a single text frame. This is ideal for a sidebar story. The settings are in `Object > Text Frame Options > Baseline Options`. You'll want to maintain the rhythm of the page, so use a value that fits with the rest of the page.

### Persuasive Baseline Grids

This is an elegant, more relaxed way to align text to our baseline without actually locking it to the baseline grid. The strategy here is to have the leading for each piece of text have a common denominator. That means all your leading values should be divisible by the same number.

In the end, we don't need to align all our text to the baseline grid. If we align only the first lines, then use leading values that are factors of a common number, everything will look like it's aligned. I call this *persuasive baseline alignment*, rather than *forced baseline alignment*.

When we're working with different size text in neighbouring columns, We can also choose to align only the first line to the baseline grid. In that case, we should try to make the leading factors of a single number.

### Cap Height Grids

A problem often occurs when tops of photos don't align with the top of the text. To solve this, we'll create a cap height grid with which we'll align our photos.

![Line up photos with the cap height]({{site.url}}/svg/baseline-grids-cap-height.svg){:width="90%"}

In figure 1, you see the unwanted space in the orange hatched space. In figure number 2, you see the cap line grid. The photos have been moved to align with it.