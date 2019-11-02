### Chapter 5 Questions

1.  In an image element, why is the `alt` attribute important?

The `alt` attribute lets the user know what the image is supposed to be if they are using a screen reader or the image doesn't load.

2.  What determines if an image element is inline or block?

An image element will be treated as a block element on its own, but can be put into other block elements and will be treated as inline.  So if you put an `<img>` before a `<p>` it will be a block, but if you put it within the `<p>` then the text will flow around it.

3.  What are the benefits of `jpg` or `png` image file formats?

The `jpg` file format is good for images that have many different colors, while `png` files are good for images that have few colors or large areas of the same color.

### Chapter 16 Questions

1.  What is the benefit of specifying the height and width of images in CSS compared to specifying in the HTML?

Controlling image size through CSS instead of HTML is useful because it cuts down on the repetition of code.  You can instead give your images classes based on size and control them all together in CSS.

2.  What is an image sprite, and why is it useful?

An image sprite is one image used to represent several parts of an interface.  An example is an image containing the 3 states of a button, normal, hovered-over, and clicked.  The sprite image technically shows all 3 states in one image, but only the relevant portion of the image is displayed to the user.  This is useful because it cuts down on the loading time by allowing the browser to only have to load one image instead of three.
