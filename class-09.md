# HTML Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing.
The <form> Element
The HTML <form> element is used to create an HTML form for user input:

<form>
.
form elements
.
</form>


The <form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

All the different form elements are covered in this chapter: HTML Form Elements.

The <input> Element
The HTML <input> element is the most used form element.

An <input> element can be displayed in many ways, depending on the type attribute.



The <label> Element
Notice the use of the <label> element in the example above.

The <label> tag defines a label for many form elements.

The <label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

The <label> element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the <label> element, it toggles the radio button/checkbox.

The for attribute of the <label> tag should be equal to the id attribute of the <input> element to bind them together.

# HTML Lists
*Unordered HTML List*
An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.

*Ordered HTML List*
An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.

*HTML Description Lists*
HTML also supports description lists.

A description list is a list of terms, with a description of each term.

# JavaScript Events
HTML Events
An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

An HTML web page has finished loading
An HTML input field was changed
An HTML button was clicked
Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

With single quotes:

<element event='some JavaScript'>

