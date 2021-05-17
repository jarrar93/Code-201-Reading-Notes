# Canvas:
* At first sight a <canvas> looks like the <img> element, with the only clear difference being that it doesn’t have the src and alt attributes.
* The <canvas> element has only two attributes, width and height.
* The canvas will initially be 300 pixels wide and 150 pixels high.
* The <canvas> element can be styled just like any normal image (margin, border, background…).
* Before we can start drawing, we need to talk about the canvas grid or coordinate space.
* There are three functions that draw rectangles on the canvas:
* fillRect(x, y, width, height) Draws a filled rectangle. strokeRect(x, y, width, height) Draws a rectangular outline. clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent.

* If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.
* fillStyle = color Sets the style used when filling shapes. strokeStyle = color Sets the style for shapes’ outlines.
![](https://miro.medium.com/max/960/1*IGKCnfK8dHAWo2z-z9A4pA.gif)
* The canvas rendering context provides two methods to render text:
fillText(text, x, y [, maxWidth]) Fills a given text at the given (x,y) position. Optionally with a maximum width to draw. strokeText(text, x, y [, maxWidth]) Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
