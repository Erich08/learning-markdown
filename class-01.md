# Introduction

The introduction portion of HTML/CSS by John Duckett starts out by reasurring its readers that despite what one might believe coding is _NOT_ that difficult to learn. It then goes on to explain the structure of the book so the reader gains a better understanding on how to utilize it to get the most out of it as well as navigating through it. The book is broken down into the three following sections:

* HTML
* CSS
* Practical

It then goes on to give a brief overview of the different ways people access the web and how websites are created. 

# Structure

Chapter one, or structure, focuses on the three main things:

1. Understanding Structure
2. Learning about markup
3. Tags and elements

> In all kinds of documents, structure is very important in helping readers to understand the messsages you are trying to convey and to navigate around the document. So, in order to learn how to write web pages, it is very important to understand how to structure documents. In this chapter you will see how HTML describes the structure of a web page, learn how tags or elements are added to your document, and write your first web page.

The book gives an example of a newspaper structure. The structure is very familiar to most and gives the reader the ability to navigate that page as it is meant to be and also make sense. 

# Extra Markup

This section focuses on the following:

* The different versions of MTL and how to indicate which version you are using
* How to add comments to your code
* Global attributes, which are attributes that can be used on any element, including the class and id attributes
* Elements that are used to group together parts of the page where no other element is suitable
* How to embed a page within a page using iframes
* How to add information about the page using a meta element
* Adding characters such as angled brackets and copyright symbols

The DOCTYPE declaration is used to tell a browser which version of HTML the page is using. 

ID and class attributes give you the ability to style _specific_ parts of your webpage without altering the rest of the page. ID elements are used to target one specific elements while classes are used for more than one element. An h1 element with the id of 'first' would be styled using the following code example:

`#first {`
    `color: red;`
`}`

A class with the name of second would be targeted this way:

`.second {`
    `color: blue;`
`}`

# HTML5 Layout

With the introduction of HTMl5, web developers no longer have to use div elements with classes or id's to identify the structure of their pages. HTML has introducted a set of elements that eliminate the necessity of divs.

So what exactly was the point of this? It gives web developers the ability to define the structure of their page as mentioned above, but it also is beneficial for those who use screen reading software to browse the web. 

The `<header>` and `<footer>` can be used for:

* The main header or footer that appears at the top or bottom of every page on the site
* A header or foorter for an individual `<article>` or `<section>` within the page.

The `<nav>` element is used to contain the major navigational blocks on the site such as the primary site navigation.

The `<article>` element acts as a container for any section of a page that could be stand alone and potentially be syndicated.

The `<aside>` element has two purposes, depending on wehther it is inside an `<article>` element or not.

There are many more, but these are just a few examples. 

# Process and Design

The website you design should be done so with your target audience in mind. The book gives multiple examples of considerations that must be taken into account:

* What is the age range of your target audience?
* Will your site appeal to more women or men? What is the mix?
* Which country do your visitors live in?
* Do they live in urban or rural areas?
* What is the average income of visitors?
* What level of education do they have?

Etc..

This chapter goes on talking about not only who your visitors are, but why are they coming to your site? What are they trying to achieve? You have to ensure that your page is designed with these questions, and more, in mind. You do not want your visitors to have a complex experience, people want to come to your site, get what they need as quickly and efficiently and with as little complexity as possible and then go on about their days.

# The ABC of programming

What is a script? It is a series of instructions that a computer can follow to achieve a goal. 

According to this chapter:

> To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.

This chapter also discusses how we as humans can accomplish very complex taks with relative ease. Specifically, taks that we do frequently that become second nature. Newer taks are more complex for us. We have to break these newer tasks down into bite-sized bits and and consume them slowly. Over time, these complex tasks become easier. The same principle applies for writing scripts. The task must be defined and then broken down based off of whatever end we are trying to achieve. The computer must be told _exactly_ what to do and _when_ to do it. 

This chapter recommends starting with the big picture of what you want to achieve and break it down into smaller, more manageable, steps. These steps are as follows:

1. Define the goal
    * First, you need to define the task you want to achieve. You can think of this as a puzzle for the ocomputer to solve.
2. Design the script
    * To design a script you split the goal out in a series of tasks that are going to be involved in solving this puzzle. This can be represented in a flow chart.
3. Code each step
    * Each of the steps needs to be written in a programming language that the computer understands. In our case, this is JavaScript.

The chapter goes on to say that you have to learn to think like a computer. Computers solve problems _programmatically_. They literally only do what they are told. 