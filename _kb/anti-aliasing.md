---
layout: type
serial: kb-subpage-anti-aliasing
title: Anti-Aliasing
deck: "Anti-aliasing is the lighter pixels you see on edges of shapes when you zoom into a raster image."
---

Screens have an actual grid of pixels. That's really ideal when all the content on the screen is made of horizontal and vertical lines. What happens when a line is angled or curved? Those lines will look all jaggy as they're depicted with those square pixels.

Enter anti-aliasing. This is the feature which adds grey pixels along those edges to make them appear smooth.

![Anti-Aliasing]({{site.url}}/svg/kb/anti-aliasing.svg){:width="40%"}

As screens gain increasingly high resolution, these pixels get smaller and smaller. That just means that these pixels are so small the eye cannot differentiate them with the device at a normal reading distance.

### Why (when) Should I Care?

In your day-to-day life as a designer, you don't need to worry about anti-aliasing too much. You don't need to be concerned with it when creating vector graphics. Only low-resolution raster images are a concern—especially those with type in them.

![Anti-Aliasing]({{site.url}}/svg/kb/anti-aliasing-photoshop.svg){:width="40%"}

In Photoshop, you can choose from various anti-aliasing settings while using the Type tool. Again, if you're exporting as SVG, these are irrelevant. If you're exporting for high-resolution displays, they're irrelevant.

This is how Adobe describes the above settings.

<dl>
	<dt>None</dt>
		<dd>Applies no anti-aliasing</dd>

	<dt>Sharp</dt>
		<dd>Type appears at its sharpest</dd>

	<dt>Crisp</dt>
		<dd>Type appears somewhat sharp</dd>

	<dt>Strong</dt>
		<dd>Type appears heavier</dd>

	<dt>Smooth</dt>
		<dd>Type appears smoother</dd>
</dl>

This is the [support page](https://helpx.adobe.com/ca/photoshop/using/editing-text.html#apply_anti_aliasing_to_a_type_layer) on Photoshop's anti-aliasing settings, in case you're interested.