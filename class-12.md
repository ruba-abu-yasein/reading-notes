# Charts

**_Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create._**
_How to draw the charts of all kinds some of chart types :_

1. bar chart
2. line chart
3. pie chart

**Drawing a pie chart**
**Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element:**
<canvas id="countries" width="600" height="400"></canvas>
Next, we need to get the context and to instantiate the chart
var countries= document.getElementById(“countries”).getContext(“2d”);
new Chart(countries).Pie(pieData, pieOptions);
Drawing rectangles
Unlike SVG,lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.
There are three functions that draw rectangles on the canvas:
fillRect(x, y, width, height) Draws a filled rectangle.
strokeRect(x, y, width, height) Draws a rectangular outline.
clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent.
Lines
For drawing straight lines, use the lineTo() method.
lineTo(x, y) Draws a line from the current drawing position to the position specified by x and y.
##Drawing text## The canvas rendering context provides two methods to render text:
fillText(text, x, y [, maxWidth]) Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
strokeText(text, x, y [, maxWidth]) Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
Styling text
There are some more properties which let you adjust the way the text gets displayed on the canvas:
font = value The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
textAlign = value Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
textBaseline = value Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
direction = value Directionality. Possible values: ltr, rtl, inherit. The default value is inherit. These properties might be familiar to you, if you have worked with CSS before.
methods
EJS Partials (Embedded JavaScript)
Mainly to reuse the same HTML across multiple views.
It makes large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file and include it wherever you need it.
How to create those partials
Example
For same navigation bar and footer appear in both the home and post view. This makes them perfect candidates for partials!
Under the views/partials/ directory create a file called navbar. EJS which will contain only the HTML for the navigation bar at the top of the home and post pages
footer.ejs in that same directory
Now that we have our partials defined, we can use them in our home.ejs and post.ejs templates!
Notes
