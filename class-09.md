# Forms

> Traditionally, the term "form" has referred to a printed document that contains spaces for you to fill in information.

Form controls:

* Adding text
    * Text input
    * Password input
    * Text Area
* Making choices
    * Radio buttons
    * Checkboxes
    * Drop-down boxes
* Submitting forms
    * Submit buttons
    * Image buttons
    * File upload

How forms work:

1. A user fills in a form and then presses a button to submit the information to the server.
2. The name of each form control is sent to the server along with the value the user enters or selects.
3. The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.
4. The server creates a new page to send back to the browser based on the informtion received.

# Lists and Tables

> There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms. 

Bullet point styles

There are three types of styles you can utilize on unordered lists:

disc, circle, or square.

```
ul {
    list-style-type: disc;
}
```

You can add images for bullet points using the followign code example:

```
ul {
    list-style-image: url("images/star.png");
}
```
# Events

> When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.

Types of events:

* UI events
* Keyboard Events
* Moust Events
* Focus Events
* Form Events
* Mutation Events

How events trigger JavaScript code:

1. Select the element node(s) you want the script to respond to.
2. Indicate which event on teh selected node(s) will trigger the response.
3. State the code you want to run when the event occurs.
