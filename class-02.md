# Text

Chapter two focuses on adding markup to the text that appears on our pages. Specifically structural and semantic markup. The book definition of both are as follows:

- **_Structural markup_** - The elements that you can use to describe both headings and paragraphs

- **_Semantic markup_** - which provides extra information; such as where _emphasis_ is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on

## Structural markup

I think it makes the most sense to continue with the current structure of this page so far and present the two different types individually.

- **Headings**
  - HTML has six different types of headings. `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`. The browser displays these from largest to smallest with `<h1>` being the largest and `<h6>` being the smallest.
- **Paragraphs**

  - Paragraphs are created utilizing the `<p>` element. The browser will display paragraphs on different lines with space in between to differentiate.

- **Bold and Italic**
  - You can bold a word, or words, by using the `<b>` element. You can also do italicize test with the `<i>` element.

There are more examples of this, but for the sake of brevity we will move on to semanctic markup.

## **_Semantic markup_**

> There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages -- they are known as semanctic markup.

As we did with structural markup above, I will cover some of the different elements that we can use to add semantic markup to our pages.

- **Strong and emphasis**

  - Simply put, the **strong** element `<strong>` will bold the text contained within the elements and `<em>` will italicize.

- **Quotations**
  - There are two elements that can be used to add quotations and they are `<blockquote>` and `<q>`.
    The difference is simply the length of the quote. For larger quotes, you would use the former and the latter for shorter ones.

# Introducing CSS

> CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.

> The key to undersstanding how CSS works is to imagine that there is an invisible box around every HTML element.

The above quote is something that is **VERY** useful to remember. If you can remember that everything is in a container then you can start to understand why things happen the way they do while using CSS.

CSS can be added to a a page by inserting a `<style>` `</style>` inside the `<head>` element. You can also do inline styling `<p style="color:red;">`This will make the paragraph red`</p>`. For clarity purposes it is better better to _link_ a style sheet to your .html files. This can be done like this `<link rel="stylesheet" href="styles.css">`.

The way CSS alters the aesthetic of a page is by targeting specific elements within the HTML file. When CSS targets one of these elements it is called a _selector_. And inside of the selector you have the declaration. Whatever you declare within that selector manipulates the targeted element(s). This could be as simple as changing the font color, font family, font size, etc..

# Basic JavaScript instructions

> JavaScript is an object-oriented computer programming language commonly used to create interactive effects within web browsers.

## Statements

> A script is a series of instructiors that a computer can follow one-by-one. Each individual instructor or step is known as a **statement**. Statements should end with a semicolon.

We can declare JavaScript variables (which are essentially containers where we can store information) using var, let, or const. To my knowledge var is not used really at all anymore. Let and const are the primary methods for declaring a variable. The difference between each is that let can be manipulated further along into the code, but const (constant) cannot be changed after it has been declared further down into your JavaScript code.

The example this particular chapter gives is as follows:

```
let today = new Date();
let hourNow = today.getHours();
let greeting;

if (hourNow > 18) {
    greeting = 'Good evening';
} else if (hourNow > 12) {
    greeting = 'Good afternoon';
} else if (hourNow > 0) {
    greeting = 'Good morning';
} else {
    greeting = 'Welcome';
}

alert(greeting);
```

All the above code is doing is taking the current time and based off of that time displaying the greeting that it corresponds with.

## Comments

Comments are a useful feature in programming languages that allow you to insert either single `//` or multi-line comments `/* */` like this in the case of JavaScript. These are very useful for explaining a particular line of code to help you remember or help another developer understand what is going on when they are looking at your code. When something is commented it will not be processed by the JavaScript interpreter.
