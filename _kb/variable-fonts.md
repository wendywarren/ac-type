---
layout: type
serial: kb-subpage-variable-fonts
title: Variable Fonts
deck: "Variable fonts are a new technology that offers greater design flexibility within a single font file."
Links: |
  - [Variable Fonts.com](https://www.variable-fonts.com/about)
  - [Can I use variable fonts on the web](https://caniuse.com/variable-fonts)
  - [More about Variable Fonts](https://web.dev/variable-fonts/)
---
Variable fonts are a new file format based on OpenType that allows the user to control all the design variants, called *axes*, all from a single font file. There's weight, width, italic, slant and optical size. Developpers have gone far beyond these axes by creating delightful transformations such as <a href="https://variablefonts.io/" title="Click the Casual button on the page." target="_blank" class="external">*casual*</a>, <a href="https://v-fonts.com/tags/C111" title="Animated Variable Font" target="_blank" class="external">*animations*</a> and <a href="https://v-fonts.com/fonts/whoa" title="Psychidelic Variable Font" target="_blank" class="external">*even stranger effects*</a>. Apple, Adobe, Microsoft and Google all worked on the development of the format.

Designers can use variable fonts in design applications like InDesign, Illustrator or Photoshop.

![Variable Fonts]({{site.url}}/svg/kb/variable-fonts.svg){:width="80%"}

They're also wonderful to use for web site and mobile app development. Very subtle adjustments can be made to the axes for various screen dimensions. 

<pre class="mono">
    .container h1 {
    font-family: some-variable-font-family;
    font-size: 5rem;
    font-variation-settings: 'wght' 375;
    font-variation-settings: 'opsz' 64;
    font-variation-settings: 'slnt' 14;
    font-variation-settings: 'ital' 1;
    font-variation-settings: 'wdth' 115;
    }
</pre>

Optical Size demonstrates just how incredible variable fonts can be. As you set your type smaller, the optical size should be set to increase the weight, and vice versa. Impressive!

You have variable fonts on your Mac now! We can launch Illustrator to test them out.

You can read more about variable fonts.

<ul class="hasBullets">
	<li><a href="https://variablefonts.io/" title="VariableFonts.io" target="_blank">VariableFonts.io</a></li>
	<li><a href="https://web.dev/variable-fonts/" title="Using variable Fonts on the Web" target="_blank">Using variable Fonts on the Web</a></li>
	<li><a href="https://css-tricks.com/getting-the-most-out-of-variable-fonts-on-google-fonts/" title="The mechanics of Google Variable fonts on the web" target="_blank">The mechanics of Google Variable fonts on the web</a></li>
	<li><a href="https://v-fonts.com/" title="A repository of free and paid variable fonts" target="_blank">A repository of free and paid variable fonts</a></li>
	<li><a href="https://variablefonts.typenetwork.com/" title="A huge wiki on variable fonts" target="_blank">Huge wiki on variable font information</a></li>
</ul>
