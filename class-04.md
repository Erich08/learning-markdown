# Links

> Links are the defining feature of the web because they allow you to move from one web page to another -- enabling the very idea of browsing or surfing.

Common types of links

- Links from one website to another
- Links from one page to another on the same website
- Links from one part of a web page to another part of the same page
- Links that open in a new browser window
- Links that start up your email program and address a new email to someone

Below is an example of a link in HTML:

`<a href="https://www.google.com">Google</a>`

href stands for hyperlink reference. The text that appears between the `<a>` element is what the person browsing the web page/site will see (this is called link text). You want to be as unambigious as possible as far as link text is concerned so that the person browsing knows exactly where that particular link will take them if they click on it.

Something else to consider is adding `target="_blank">` inside of the open `<a>` element. This will whatever the destination page is in a new tab that way the user is still on your wesbite and doesn't have to navigate back if they want to return. They just simply have to click the tab with your page open.

> Generally you should avoid opening linnks in a new window, but if you do, it it considered good practice to inform users that the link will open in a new window before they click on it.

# Layout

The most frustrating aspect of CSS that I find is understanding how to position all of my elements in a way that they don't conflict with one another (ie block elements/inline elements) and if they do, understanding how to correct the issue to achieve the aesthetic that you are looking for.

> CSS treats each HTML element as if it is in its own box. This box will either be a **block-level** box or an **inline** box.

The difference between that two is that _block-level_ elements will start on a new line and _inline_ elements flow in between surrounding text. If you do not understand this it leads to inumerable amounts of frustration with limited knowledge of CSS. You know what it it is that you would like it to do, but you don't full understand **how** to accomplish it.

Containing Elements

> If one block-level element sits inside another block-level element then the outer box is know as the containing or parent element.

# Functions, Methods, and Objects

> Browsers require very detailed instructions about what we want them to do. Therefore, complex scripts can run to hunderes (even thousands) of lines. Programmers use functions, methods, and objects to organize their code.

What is a function?

> Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).

As you can probably discern from the above text, this gives programmers the ability to reduce the amount of code they have to write and allows them to call this function in different parts of their programming whenever needed.

Variable scope

> The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is know as the variable's scope.

What is an object?

> Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables and functions take on new names.
