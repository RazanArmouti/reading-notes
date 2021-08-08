# Read: 12 - Docs for the HTML <canvas> Element & Chart.js

## ***EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS***
 A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.\
 The great things about Chart.js are that it’s simple to use and really very flexible. Plus, once you’ve mastered the basics here, you’ll discover that there are tons of options listed in the documentation.


## ***Chart.js***
 It's easy to get started with Chart.js. All that's required is the script included in your page along with a single canvas node to render the chart.

## ***Basic usage of canvas***
 a canvas looks like the img element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the canvas element has only two attributes, width and height. These are both optional and can also be set using DOM properties.

## ***Drawing shapes with canvas***
 * The grid
 * Drawing rectangles
 * Lines
 * Drawing a triangle
 * Arcs
 * Bezier and quadratic curves


## ***Applying styles and colors***
 Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

## ***Drawing text***
 The canvas rendering context provides two methods to render text:

 1. fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
 2. strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.