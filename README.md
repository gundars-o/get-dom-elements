# get-dom-elements

### Problem:

1) Spending time on writing a new line of code for assigning HTML element to js variable/constant:
const newElement = document.getElementById( 'new-element' );

2) Spending time generating new names of variables, even if it is just converting lowercase-dash-lowercase to camelCase.

3) Spending time in case you need to find this element in HTML, especially when lowercase-dash-lowercase was converted to camelCase.

### Solution:

1) Assign elements defined in HTML code to js variables automatically by adding a simple function in the beginning of js.

2) If you need to use some HTML element in js, start the name of new js variable/constant with 3 symbols 'dom' and add the name of newly created variable as the first class name for the element in HTML.

### Result:

Improved speed of writing js code.

Improved speed of reading js code because of equal names of js variables and HTML elements.
