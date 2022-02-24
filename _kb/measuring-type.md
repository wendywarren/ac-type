---
layout: type
serial: kb-subpage-measuring-type
title: Measuring Type
deck: "This page began with the question <i>Can I measure printed type with a ruler?</i>"
---
I actually have a typographic ruler (or *gauge*) in my office. I tried to measure type printed on a page that I printed. I knew it was 12 points in InDesign, but it didn't measure twelve points according to the ruler.

![Measuring type]({{site.url}}/svg/kb/measuring-type.svg){:width="90%"}

As you see in the graphic above, there's a measurement called *Point Size*. This measurement is the height of the container of all the glyphs in a type family at a specified size. This corresponds to the number in the *Size* menu in your design software. It is not the measurable height of the printed glyph on the page. Theoretically, this container *could* measure 72 points tall but contain a capital M that measures 8 points.

![Measuring Type Difference]({{site.url}}/svg/kb/measuring-type-difference.svg){:width="60%"}

Here, you see that the upper case M set in Fira Sans at 72 points is much taller than the same glyph set in Mrs. Eaves at 72 points.

So the answer to my is question is *No*. One cannot use a ruler to accurately measure type on a printed page in order to enter that number in their design software to reproduce that size type. The most valuable tool in visually measuring type is the experienced, trained eye.

#### Points & Picas

We use points and picas to measure type in print. There's a long history about how these units of measure evolved. There are different sizes of points which have been created by prominent typographers in Europe. Suffice it to say, today, the point we use is unfortunately based on the American inch, which has [no intrinsic significance](https://en.wikipedia.org/wiki/Inch#History){:target="_blank"}.

![Picas, Points & Inches]({{site.url}}/svg/kb/points-picas-inches.svg){:width="90%"}

#### The Em

An Em is a relative measurement which is equal to the given point size of type. If you have a word set at 32 points, then 1 em is equal to 32 points. The goal is to have a relative sizing system rather than an absolute one.

![Em Type system]({{site.url}}/svg/kb/measuring-type-ems.svg){:width="60%"}

Let's say your basis size is 12 points. Your em size will be 12 points. With this, you can set up a type system by increasing by half with each step. You're just adding 50% to each number.

> If you've ever wondered how large to make your paragraph spacing or their first line indents, start with 1 Em and adjust if needed.

One thousandths of Ems?! That's what page layout software applications use to calculate such measurements such as kerning and tracking. This is useful, because the cumulative effects of tracking can be great. Each time you track in text, that tightening is applied to the space between each glyph. The overall effect needs to be set at a *micro* level.

#### White Space

When designing a typeface, typographers even need to decide the size of the spaces between things. This is generally termed *white space*. These are the units of measure.

![White space measurement]({{site.url}}/svg/kb/measuring-type-whitespace.svg){:width="50%"}

Em Space
: Equal in width to the size of the type. In 24‑point type, an Em space is 24 points wide. Frustratingly, the Em dash is not necessarily 1 Em wide! 😭 The Em space should always be.

![Em space Vs Em Dash]({{site.url}}/svg/kb/em-space-vs-em-dash.svg){:width="60%"}

En Space 
: One‑half the width of an em space. Old-school type folks call this a *nut* because En space sounds to close to Em space.

Thin Space 
: *Usually* one‑eighth the width of an em space. You may want to use a thin space on either side of an em dash or en dash.

Hair Space 
: *Approximately* one‑twenty‑fourth the width of an em space. These can be used to create a separation between punctuation glyphs.

Em measurements are most often used when coding CSS. The issue is that the em size is always relative to the parent type size in the cascade. This can get confusing really quickly. Enter the REM.

#### The REM

REM stands for *Root Em*. The difference here is that all REM measurements are anchored in the root element type size. If you define your base type to measure 16 pixels, all other type in rems will be a multiplier of that measurement.