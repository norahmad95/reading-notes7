# class 12


## Charts

a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

### Setting up

 Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script.

 ### Drawing a line chart

  canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page,Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element

  Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart.


  ## canvas tag :

 it only has two attributes, width and height. These are both optional and can also be set using DOM properties.
 the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

 **note**: ***Note: If your renderings seem distorted, try specifying your width and height attributes explicitly in the (canvas) attributes, and not using CSS.***

 creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown.


 ### Drawing shapes with canvas :

 [visit this link to see the steps](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

 ### Applying styles and colors :
 
 * Colors:

 there are two important properties we can use: fillStyle and strokeStyle.

 1- fillStyle = color
Sets the style used when filling shapes.
 2- strokeStyle = color
Sets the style for shapes' outlines.

* Line styles :

There are several properties which allow us to style lines.

 1- lineWidth = value
Sets the width of lines drawn in the future.
 
 2- lineCap = type
Sets the appearance of the ends of lines.

 3- lineJoin = type
Sets the appearance of the "corners" where lines meet.

 4- miterLimit = value
Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the    junction becomes.
 
 5- getLineDash()
Returns the current line dash pattern array containing an even number of non-negative numbers.
setLineDash(segments) Sets the current line dash pattern.

 6- lineDashOffset = value
Specifies where to start a dash array on a line.

## drawing text :

The canvas rendering context provides two methods to render text:

 1- fillText(text, x, y [, maxWidth] 
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

 2- strokeText(text, x, y [, maxWidth])
trokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
