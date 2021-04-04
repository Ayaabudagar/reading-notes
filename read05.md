# **What is the definition of JavaScript loop?**
JavaScript - For Loop. The 'for' loop is the most compact form of looping. The loop initialization where we initialize our counter to a starting value. The initialization statement is executed before the loop begins. The test statement which will test if a given condition is true or not.

**Is there a way to loop over an array in JavaScript?**
Looping over an array and any other objects in JavaScript is a common problem lots of programmers encounter the most. There are several ways to loop over an array in JavaScript. Let’s have a look and find the optimal one for you.

The JavaScript loops are used to iterate the piece of code using for, while, do while or for-in loops. It makes the code compact. It is mostly used in array.

There are four types of loops in JavaScript.

for loop
while loop
do-while loop
for-in loop
**The JavaScript loops** are used to iterate the piece of code using for, while, do while or for-in loops. It makes the code compact. It is mostly used in array.

There are four types of loops in JavaScript.

1) for loop
while loop
do-while loop
for-in loop

<script>  
for (i=1; i<=5; i++)  
{  
document.write(i + "<br/>")  
}  
</script>  


2) JavaScript while loop

The JavaScript while loop iterates the elements for the infinite number of times. It should be used if number of iteration is not known. The syntax of while loop is given below.
<script>  
var i=11;  
while (i<=15)  
{  
document.write(i + "<br/>");  
i++;  
}  
</script>  

Next →← Prev
JavaScript Loops
The JavaScript loops are used to iterate the piece of code using for, while, do while or for-in loops. It makes the code compact. It is mostly used in array.

There are four types of loops in JavaScript.

for loop
while loop
do-while loop
for-in loop
1) JavaScript For loop
The JavaScript for loop iterates the elements for the fixed number of times. It should be used if number of iteration is known. The syntax of for loop is given below.


for (initialization; condition; increment)  
{  
    code to be executed  
}  
Let’s see the simple example of for loop in javascript.

<script>  
for (i=1; i<=5; i++)  
{  
document.write(i + "<br/>")  
}  
</script>  
Test it Now
Output:

1
2
3
4
5

 
2) JavaScript while loop

The JavaScript while loop iterates the elements for the infinite number of times. It should be used if number of iteration is not known. The syntax of while loop is given below.

while (condition)  
{  
    code to be executed  
}  
Let’s see the simple example of while loop in javascript.

<script>  
var i=11;  
while (i<=15)  
{  
document.write(i + "<br/>");  
i++;  
}  
</script>  

3) JavaScript do while loop
The JavaScript do while loop iterates the elements for the infinite number of times like while loop. But, code is executed at least once whether condition is true or false. The syntax of do while loop is given below.

<script>  
var i=21;  
do{  
document.write(i + "<br/>");  
i++;  
}while (i<=25);  
</script>  