# **HTML Text**
When coding HTML, text is a very straightfoward thing to add and format. In HTML, text can be formatted in much the same way that a typical word processor (such as Word) formats text. You can set bold text and italics. You can change the color of your text with HTML. You can change the alignment of your text (i.e. left, center, right, justified). You can change the font and font size. Pretty much most things you will need to do can be accomplished using HTML.

Actually HTML text usually gets formatted using Cascading Style Sheets (CSS). CSS works together with HTML so that you can change the style or look of your web pages.

HTML Text Editor
The easiest way to see how text is formatted in HTML is to use this free HTML text editor to style your text. This uses a WYSIWYG interface where you simply click the buttons - just like in Word.

HTML Text Codes
Here are some HTML text and font links:

HTML Bold
Text Code
Font Code
Text Color Code
HTML Links Code

# What is CSS

CSS stands for Cascading Style Sheets. It is the language for describing the presentation of Web pages, including colours, layout, and fonts, thus making our web pages presentable to the users.

CSS is designed to make style sheets for the web. It is independent of HTML and can be used with any XML-based markup language. Now let’s try to break the acronym:

        Cascading: Falling of Styles
        Style: Adding designs/Styling our HTML tags
        Sheets: Writing our style in different documents
 
 

 CSS Comment
Comments don’t render on the browser
Helps to understand our code better and makes it readable.
Helps to debug our code
Two ways to  comment:
Single line 
 /*<h6> This represents the most/ least important line of the doc. </h6>*/
Here is how to comment out multiple lines:


 /*
         h1
     {
     color: red;
     text-align: center;
      } 
      */
 CSS How-To 
There are 3 ways to write CSS in our HTML file.
Inline CSS
Internal CSS
External CSS
Priority order
Inline > Internal > External
  Inline CSS

Before CSS this was the only way to apply styles
Not an efficient way to write as it has a lot of redundancy
Self-contained 
Uniquely applied on each element
The idea of separation of concerns was lost
Example:
<h3 style=” color:red”> Have a great day </h3>
<p  style =” color: green”> I did this , I did that </p>
  

  Internal CSS

With the help of style tag, we can apply styles within the HTML file
 Redundancy is removed
But the idea of separation of concerns still lost
Uniquely applied on a single document
Example:
    < style>
              h1{
                     color:red;
                   }
     </style>  
    <h3> Have a great day </h3>
  External CSS

With the help of <link> tag in the head tag, we can apply styles
Reference is added 
File saved with .css extension
Redundancy is removed
The idea of separation of concerns is maintained
Uniquely applied to each document
Example:
<head>
 <link rel="stylesheet" type="text/css" href="name of the Css file">
</head>
            h1{
                     color:red;         //.css file
                 }

# Decisions and Loops 

Scripts often need to behave differently depending upon how the user interacts with the web
page and/or the browser window itself. To determine which path to take, programmers often
rely upoDecisions and Loopsn the following three concepts:
*EVALUATIONS*
You can analyze values in your scripts to determine whether or note they
match expected results.
DECISIONS
Using the results of evaluations, you can decide which path your script should go down.

LOOPS There are also many occasions where you will want to perform the same
set of steps repeatedly.

# A switch statement 
starts with a variable called the switch value.
Each case indicates a possible value for this variable and the code that should run if the
variable matches that value.
Here, the variable named 1 eve l is the switch value. If the value of the l eve 1 variable is the string One,
then the code for the first case is executed. 
If it is Two, the second case is executed. If it is Three, the third case is executed. If it is none of these, the code for the defaul t case is executed.
The entire statement lives in one code block (set of curly braces), and a colon separates the option
from the statements that are to be run if the case matches the switch value.
At the end of each case is the break keyword. It tells the JavaScript interpreter that it has finished with
this switch statement and to proceed to run any subsequent code that appears after it.

**IF ... ELSE**
• There is no need to provide an el se option. (You can just use an if
statement.)
• With a series of if statements, they are all checked even if a match has been found
(so it performs more slowly than switch).
**SWITCH**
• You have a default option that is run if none of the cases match.
• If a match is found, that code is run; then the break statement stops the rest of
the switch statement running (providing better performance than multiple i f
statements).