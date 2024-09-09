##D3 has several methods that let you add and change elements in your document.

The select() method selects one element from the document. It takes an argument for the name of the element you want and returns an HTML node for the first element in the document that matches the name. 



##Two other useful methods are append() and text().

The append() method takes an argument for the element you want to add to the document. It appends an HTML node to a selected item, and returns a handle to that node.

The text() method either sets the text of the selected node, or gets the current text. To set the value, you pass a string as an argument inside the parentheses of the method.

##D3 also has the selectAll() method to select a group of elements. It returns an array of HTML nodes for all the items in the document that match the input string.


##The data() method is used on a selection of DOM elements to attach the data to those elements. 

##D3 has the attr() method to add any HTML attribute to an element, including a class name.

##The attr() method works the same way that style() does. It takes comma-separated values, and can use a callback function.


