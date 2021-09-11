# What is CSS?

CSS stands for **C**ascading **S**tyle **S**heets. At a very basic level **CSS** are the aesthetics that are added to make the base structure of HTML more presentable and pleasing to the eye. CSS utilizes _selectors_ to add different properties and values such as color, font size, padding, margin, etc. to HTML elements.

## The syntax

According to MDN:

>CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

Here is a simple example of a CSS rule:

> `h1 {`
    `color: red;`
    `size: 5px;`
> `}`

The _selector_ targets the `<h1>` element. Following the selector we have _curly braces_ that contain the _declarations_. These declarations are what _styles_ the `<h1>` element.

## How do we link CSS file to our HTML file?

This can be done by _referencing_ the style sheet file inside the `<head></head>` section by linking it to your style sheet. I have provided an example of this below:

* `<!DOCTYPE html>`
`<html>`
`<head>`
`<link rel="stylesheet" href="mystyle.css">`
`</head>`
`<body>`

`<h1>This is a heading</h1>`
`<p>This is a paragraph.</p>`

`</body>`
`</html>`


You could link the same style sheet to multiple .html files **OR** you could have a style sheet for each indivdual .html file.