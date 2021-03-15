# Charts 


![Alt Text](https://i.pinimg.com/originals/3a/e9/30/3ae9305f77174913efa9265f6cc720dd.gif)


Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. 
They’re easier to look at and convey data quickly, but they’re not always easy to create.

Setting up
The first thing we need to do is download Chart.js.
Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:


_Drawing a line chart_

```
<canvas id="buyers" width="600" height="400"></canvas>

```
At first sight a canvas looks like the  img element, with the only clear difference being that it doesn't have the src and alt attributes.
Indeed, the <canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties.
When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, 
but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.


Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:
```
<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>
(We can actually pass some options to the chart via the Line method, but we’re going to stick to the data for now to keep it simple.)

```
Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart. Add this immediately above the line that begins ‘var buyers=’:
```
var buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}
```
If you test your file in a browser you’ll now see a cool animated line graph.

_Drawing a pie chart_

Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element:
```
<canvas id="countries" width="600" height="400"></canvas>
````
Next, we need to get the context and to instantiate the chart:
```
var countries= document.getElementById("countries").getContext("2d");
new Chart(countries).Pie(pieData, pieOptions);
You’ll notice that this time, we are going to supply some options to the chart.
```

Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler, we just need to supply a value and a color for each section:
```
var pieData = [
	{
		value: 20,
		color:"#878BB6"
	},
	{
		value : 40,
		color : "#4ACAB4"
	},
	{
		value : 10,
		color : "#FF8153"
	},
	{
		value : 30,
		color : "#FFEA88"
	}
];
```
Now, immediately after the pieData we’ll add our options:
```
var pieOptions = {
	segmentShowStroke : false,
	animateScale : true
}
```
These options do two things, first they remove the stroke from the segments, and then they animate the scale of the pie so that it zooms out from nothing.


