##D3 has several methods that let you add and change elements in your document.

The select() method selects one element from the document. It takes an argument for the name of the element you want and returns an HTML node for the first element in the document that matches the name. 



##Two other useful methods are append() and text().

The append() method takes an argument for the element you want to add to the document. It appends an HTML node to a selected item, and returns a handle to that node.

The text() method either sets the text of the selected node, or gets the current text. To set the value, you pass a string as an argument inside the parentheses of the method.

##D3 also has the selectAll() method to select a group of elements. It returns an array of HTML nodes for all the items in the document that match the input string.


##The data() method is used on a selection of DOM elements to attach the data to those elements. 

##D3 has the attr() method to add any HTML attribute to an element, including a class name.

##The attr() method works the same way that style() does. It takes comma-separated values, and can use a callback function.

##Note: Multiplying each data point by the same constant only alters the scale. It's like zooming in, and it doesn't change the meaning of the underlying data.

##SVG stands for Scalable Vector Graphics.

Here "scalable" means that, if you zoom in or out on an object, it would not appear pixelated. It scales with the display system, whether it's on a small mobile screen or a large TV monitor.

##SVG is used to make common geometric shapes. Since D3 maps data into a visual representation, it uses SVG to create the shapes for the visualization. SVG shapes for a web page must go within an HTML svg tag.

CSS can be scalable when styles use relative units (such as vh, vw, or percentages), but using SVG is more flexible to build data visualizations.


##The next step is to create a shape to put in the svg area. There are a number of supported shapes in SVG, such as rectangles and circles. They are used to display data. For example, a rectangle (<rect>) SVG shape could create a bar in a bar chart.


##n SVG, a rect shape is colored with the fill attribute. It supports hex codes, color names, and rgb values, as well as more complex options like gradients and transparency.

##D3 lets you label a graph element, such as a bar, using the SVG text element.

Like the rect element, a text element needs to have x and y attributes, to place it on the SVG. It also needs to access the data to display those values.


##A tooltip shows more information about an item on a page when the user hovers over that item. There are several ways to add a tooltip to a visualization. This challenge uses the SVG title element.

title pairs with the text() method to dynamically add data to the bars