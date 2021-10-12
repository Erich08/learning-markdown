# Object Literals

> Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, wariables and functions take on new names.

In an object, a variable becomes known as a property. Those properties tell us about that particular object. If a function is part of an object it becomes a method.

Objects have properties and methods with a name as well as a value. These names are referred to as **_keys_**.

The keys must be named individually because they are used to access the values in which they are associated with.

> The value of a property can be a string, number, Boolean, array, or even another object. The value of a method is always a function.

In JavaScript:

- Variables have a name and you can assign them a value of a string, number, or Boolean.

- Arrays have a name and a group of values. (Each item in an array is a name/value pair because it has an index number and a value.)

- Named functions have a name nad a value that is a set of statements to run if the function is called.

- Objects consist of a set of name/value pairs (but the names are referred to as keys).

# Document Object Model (DOM)

> The Document Object Model specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

The DOM is called an object model bcause the model is made of objects (who knew).

The DOM tree is a model of a web page.

> When you access any element, attribute, or text node, you navigate to it via the document node. It is the starting point for all visits to the DOM tree.

> Each node is an object with methods and properties. Scripts access and update this DOM tree (not the source HTML file). Any changes made to the DOM tree are reflected in the browser.

Accessing and updating the DOM tree involes two steps:

1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.

Below I have listed some common ways to access elements in the DOM.

- getElementById()

  - Use the value of an element's id attribute(which should be unique within the page).

- querySelector()

  - Uses a CSS selector, and returns the first matching element.

- getElementsByClassName()

  - Selects all elements that have a specific value for their class attribute.

- getElementsByTagName()

  - Selects all elements that have the specified tag name.

- querySelectorAll()

  - Uses a CSS selector to select all matching elements.

- parentNode

  - Selects the parent of the current element node(which will return just one element).

- previousSibling/nextSibling

  - Selects the previous or next sibling from the DOM tree

- firstChild/lastChild
  - Select the first or last child of the current element.

> The terms **elements** and **element nodes** are used interchangeably but when people say the DOM is working with an element, it is actually working with a node that _represents_ that element.

_Remember_ we are only manipulating the _nodes_ within the DOM and NOT the HTML source file. If you keep that in mind when reading the above quote it will help it make more sense.
