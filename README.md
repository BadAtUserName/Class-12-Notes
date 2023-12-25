# Class-12-Notes

Class 12 reading

JavaScript Canvas

Javascript Canvas<br> 
Requires at least two attributes<br>
Width<br> 
Height<br>
B. Can be accessed with Dom properties<br>
C. Canvas element required a closing tag unlike image.<br>
D. Canvas is blank to draw something use
	1. getContext() returns a context object<br>
		a. Takes one argument which is the type of context like  2d<br> 
E. 2D context<br> 
	1. 2d drawing context features methods for drawing simple 2d shape<br>
		a. Paths<br>
		b. Rectangles<br>
		c. Arc<br>
	2. Coordinates begin in the upper left of the canvas element which is 0,0 coordinates<br>
	3. All coordinates are calculated  in relation to the 0, 0 with x increasing to the right and y increasing to the bottom<br>
		a. By default the width and heigh determine the number of pixels available in each direction<br>

4. Fills and Strokes<br>
		a. Fill, fills in a shape wit something like a color or gradient or image<br>
		b. Stroke adds color at edges of shape<br>
		c. fillStyle and strokeStyle determine fill and stroke styles<br>
			i. Can set these props to a string, gradient object, or pattern object<br>
		

Chart.js Documentation

Why chart.js
Most popular<br>
Created and announced in 2013<br>
Open source maintained by active community<br>
II. Features<br>
	A. Provides
		1. Frequently used chart types<br>
		2. Plugins<br>
		3. Customization<br> 
		4. Reasonable builtin chart types
		5. Can combine several chart types into mixed chart.
	B. Highly customizable with custom plugins to created<br>
		1. Annotations<br>
		2. Zoom<br>
		3. Drag-and-drop<br>
II. Defaults<br>
	A. chartJS comes with defaults that make it very ease to start.<br>

III. Integrations<br>
	A. Comes with built-in TypeScript typings and is compatible with pop frameworks.<br> 
	B. Can use charts directly or used wrapper packages<br>

IV. Dev Experiance<br>
	A. Has thorough documentation<br> 
	B. Active community members<br>
	C. Active stack overflow 

V. Canvas rendering<br>
	A. Renders elements in HTML5 canvas.<br>
		1. Makes very  performant especially for large datasets and complex visualizations<br>

VI. Performance<br>
	A. Well suited for large datasets can be efficiently ingested using internal format.<br>
	B. Can skip data parsing and normalization.<br> 
	C. Data decimation can config a sample to the data set and reduce size b4 rendering<br> 


Easily Create stunning Animated Charts with Chart.js<br>

Create animated charts<br>
Charts display data visually better than tables and no one will try to turn it into a layout<br>

II. Setting up<br>
	A. First download<br>
	B. Then copy chart.min.jas out of unzipped folder and into directory being used. 
	C. See following for how to instuctions  




##Reading questions

What does the <canvas> allow a developer to achieve? 
	a. It allow the dev to make a 2d drawing using Javascript

2. What is the importance of the closing </canvas> tag?
	a. Content between the opening and closing tags is fallback content that will be displayed if the browser doesn’t support the element

3. Explain what the getContext() method does. 
	a. The getContext method returns a context render image. It takes one argument being the the of context.

Chart.js Documentation
	
What is chart.js and how can it be brought into your project? 
	a. It is a free opensoruc javascript library for data visualization 
	cited: https://en.wikipedia.org/wiki/Chart.js 
	It can be brought into your project by downloading it and placing it in the directory you are using. 

2. List 3 different chart types you can create using Chart.js
	a. You can make many types of charts here are three…1. A bubble chart 2. Radar chart, 3. A scatter chart.


Easily create animated charts with chart.js

What are some advantages to displaying data via a chart over a table? 
	a. Charts display data visually better than tables and no one will try to turn it into a layout

2. How could chart.js aid your previously created applications visually? 
	a. ChartJs. Could take the data from the table on salmon cookies and then creat a chart showing each locations sales in a fun and exciting way that is more accessible and easier for people to interact with.
	


##Things i want to know more about
  grid and flexbox i do not understand. 
