---
layout: type4
serial: level-4-assignment-2-menu-subpage-the-type
---
For this project, there are no specific limits on the use of type except for your judgement of what's appropriate for the client. You should be applying the rules you've learned to date. Of course, you must only be choosing from [Adobe Type](https://fonts.adobe.com){:target="_blank"}.

### Display Typefaces

The style of your chosen restaurant will dictate your type selection. Some type designs are closely related to certain cultures, but we must avoid stereotypes. Typefaces which mimics a foreign language can be offensive.

Many display faces have only one instance. If you can find a family with multiple instances, it will give you that much more flexibility.

### Serif & Sans-Serif

You have the choice of working with a serif and a sans, or both, in addition to your display face. As usual, you'll need to make a sound pairing with them all.

### Elements of a Menu Design

The *minimum* elements of your menu design will include

<ul class="hasBullets">
	<li>Restaurant Name</li>
	<li>Content</li>
	<li class="second">section titles</li>
	<li class="second">item names</li>
	<li class="second">item descriptions</li>
	<li class="second">item prices</li>
	<li class="second">item modifiers</li>
	<li class="second">ingredient statements (vegan, nuts, etc…)</li>
	<li class="second">call-outs for specials</li>
	<li class="second">contact information</li>
	<li class="second">social media links</li>
	<li class="second"><a href="https://svgqrcodes.com/?lang=en" title="QR Code Generator" target="_blank">QR code</a> to restaurant web site</li>
</ul>

You can move these items around to suit your design.

### Technical Considerations

While working in InDesign, we want to put into practice what you've learned to date.

<ul class="hasBullets">
	<li>Use as few InDesign text frames as possible</li>
	<li>Use paragraph styles throughout</li>
	<li>Use a tab character rather than multiple spaces.</li>
	<li>You should not have more than one consecutive paragraph break.</li>
</ul>

### Clean Up the Content

The text for your menu is going to need some cleaning up. You'll remove multiple paragraph breaks. Some of the menu items are in upper case letters. That'll need to change.

> Let InDesign do most of this work. Type in the text the very least possible, if at all.

#### GREP Patterns

InDesign's `Edit > Find/Change…` command is going to be your friend here. Use it wisely and attentively.

This is a little primer on GREP (or regex) patterns. You can use these in the Find/Change `cmd-f` dialogue in InDesign. Be sure to click on the `GREP` tab in the Find/Change dialogue.

You can find a price like this `$12` with `\$\d+`. `\$` finds a dollar sign. `d+` finds one or more digits.

See [this table](https://github.com/ziishaned/learn-regex/blob/master/README.md#2-meta-characters){:target="_blank"} for the definitions of more *meta characters*.

If you're interested in learning more about GREP patterns, these sites will get you going. [Learn REGEX The Easy Way](https://github.com/ziishaned/learn-regex/blob/master/README.md) and [Regexer](https://regexr.com) and [Adobe Support doc](https://helpx.adobe.com/indesign/using/find-change.html).

You can also use `Type > Change Case…`. If you're using small caps, you can set that in your paragraph styles.