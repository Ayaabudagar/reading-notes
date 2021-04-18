# HTML Tables

Define an HTML Table
The <table> tag defines an HTML table.

Each table row is defined with a <tr> tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a <td> tag.

By default, the text in <th> elements are bold and centered.

By default, the text in <td> elements are regular and left-aligned.
Example
A simple HTML table:

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>

*HTML Table - Add a Border*
To add a border to a table, use the CSS border property

*HTML Table - Collapsed Borders*
To let the borders collapse into one border, add the CSS border-collapse property

*HTML Table - Add Cell Padding*
Cell padding specifies the space between the cell content and its borders.

If you do not specify a padding, the table cells will be displayed without padding.

To set the padding, use the CSS padding property

*HTML Table - Left-align Headings*
By default, table headings are bold and centered.

To left-align the table headings, use the CSS text-align property

*HTML Table - Add Border Spacing*
Border spacing specifies the space between the cells.

To set the border spacing for a table, use the CSS border-spacing property

*HTML Table - Cell that Spans Many Columns*
To make a cell span more than one column, use the colspan attribute

*HTML Table - Cell that Spans Many Rows*
To make a cell span more than one row, use the rowspan attribute

*HTML Table - Add a Caption*
To add a caption to a table, use the <caption> tag

*A Special Style for One Table*
To define a special style for one particular table, add an id attribute to the table

# JavaScript Object Constructors
Example
function Person(first, last, age, eye) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eye;
}

*Object Types (Blueprints) (Classes)*
The examples from the previous chapters are limited. They only create single objects.

Sometimes we need a "blueprint" for creating many objects of the same "type".

The way to create an "object type", is to use an object constructor function.

In the example above, function Person() is an object constructor function.

Objects of the same type are created by calling the constructor function with the new keyword

The this Keyword
In JavaScript, the thing called this is the object that "owns" the code.

The value of this, when used in an object, is the object itself.

In a constructor function this does not have a value. It is a substitute for the new object. The value of this will become the new object when a new object is created.

**To add a new property to a constructor, you must add it to the constructor function**
function Person(first, last, age, eyecolor) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eyecolor;
  this.nationality = "English";
}
Adding a Method to a Constructor
Your constructor function can also define methods