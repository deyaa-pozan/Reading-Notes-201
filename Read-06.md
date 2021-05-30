# problem domain

***
To Finish a task.
You must first understand the Problem Domain
By breaking it down into smaller tasks
***

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

* Make the problem domain easier
* Get better at understanding the problem domain

# object


***
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names. 
***

![object](https://fireship.io/courses/javascript/img/js-object-props.png)

# HTML DOM

***
When a web page is loaded, the browser creates a Document Object Model of the page.

The HTML DOM model is constructed as a tree of Objects:
***

![DOM](https://www.w3schools.com/js/pic_htmltree.gif)

### METHODS THAT RETURN A SINGLE ELEMENT NODE: 

* getElementByld() : 
`Selects an individual element given the value of its i d attribute .
The HTML must have an id attribute in order for it to be selectable`

* querySelector():
`Uses CSS selector syntax that would select one or more elements .
This method returns only the first of the matching elements. `

### METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST): 

* getEl ementsByClassName():
1Selects one or more elements given the value of their cl ass attribute.
The HTML must have a cl ass attribute for it to be selectable.
This method is faster than querySe1ectorA11 ()

* getElementsByTagName():
`Selects all elements on the page with the specified tag name.
This method is faster than querySe 1ectorA11 ()`

* querySelectorAll():
`Uses CSS selector syntax to select one or more elements and returns all
of those that match.`