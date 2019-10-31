# Day 2 Exercises

### Chapters 3 and 4 Questions

1.  There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?

An ordered list is where the order matters, so something like `1. 2. 3.` or `a) b) c)` where an unordered list the order doesn't matter as much, so it is just bullet points.  Definition lists are just what they sound like, where there is a term, followed by its definition, these are usually reverse indented (the term is not indented, but the definition is).

2.  What is the basic structure of an element used to link to another website?

the basic structure of a link element is `<a></a>` however, you almost always need to ad a `href` attribute to the opening tag, so an example link element would look like this `<a href="website.com">Clickable text</a>`

3.  What attribute should you include in a link to open a new tab when the link is clicked?

You would need to add a space and `target="_blank"` after your `href` attribute in order for it to open a new tab when clicked.

4.  How do you link to a specific part of the same page?

By assigning id tags such as `id="contents"` to an element, you can link to the specific part of the page via an href such as `href=#contents` or `href="www.website.com/#contents"` if linking to a specific part of a page you are not currently on.

### Chapters 10, 11, and 12 questions

  1.  What is the purpose of CSS?

CSS determines they style of the content, it describes how things will appear, where HTML describes what will appear.

  2.  What does CSS stand for? What does cascading mean in this case?

CSS stands for Cascading Style Sheets, cascading refers to the fact that the styles apply one after another, so that the last style described in the stylesheet will overwrite any previous styles unless otherwise specified.

  3.  What is the basic structure of a CSS rule?

A CSS rule is made up of a selector and a declaration (contained within {} curly brackets). The selector indicates the element being styled, and the declaration indicates how it will be styled.  The declaration is also made up of two parts, a property and a value, separated by a colon.  The property indicates the aspect that you want to change, and the value specifies a setting of that property. You can define multiple properties in a declaration by separating them with a semi-colon.

  4.  How do you link a CSS stylesheet to your HTML document?

You can link a CSS stylesheet by using the `link` element, this is an empty element, so no closing tag is required; however, you will need to add a `href` attribute to specify the file path of the CSS file.

  5.  When is it useful to use external stylesheets as opposed to using interal CSS?

It is most useful to use external stylesheets when you have multiple web pages with the same styling.  This makes it quicker to load, and easier to edit all of them at once.

  6.  Describe what a color hex code is.

A color hex code is a series of 6 numbers preceded by a # that indicate the amount of red, green, and blue combine to create a color.  The six digits can be broken down into 3 pairs of two digits each, where the first pair represents the amount of red, the second pair represents the amount of green, and the last pair represents the amount of blue.

  7.  What are the three parts of an HSL color property?

HSL stands for hue, saturation, and lightness.  Hue is the color, expressed as an angle of a color wheel. Saturation is how much gray a color contains expressed as a percentage, high percentages appear vibrant, while low percentages are washed out. Lightness is the amount of black or white in a color, expressed as a percentage. At 50% the color is normal, while it becomes closer to black as it approaches 100%, and closer to white as it approaches 0%.

  8.  In the world of typeface, what are the three main categories of fonts? What are the differences between them?

The three main font categories are serif, sans-serif, and monospace.  Serif fonts have extra details at the ends of strokes, while sans-serif fonts have straight ends, creating a cleaner look.  Monospace fonts have the same width for every letter, making text easier to follow, very useful for coding.

  9.  When specifiying font-size, what are the main three units used?

The main units used for font-size are pixels, percentages, and ems. Pixels are relative to the size of the screen, percentages are relative to the size of the default text, and ems are relative to the width of the letter m in the chosen font.
