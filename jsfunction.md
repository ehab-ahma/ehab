# java script function
Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it

### Defining functions
There are two type of defining the function 

- Function declaration which contain 

1 - The name of the function.

2- A list of parameters to the function, enclosed in parentheses and separated by commas.

3- The JavaScript statements that define the function, enclosed in curly brackets, {...}.
For example

function square(number) {

  return number * number;

}
- Function expressions

While the function declaration above is syntactically a statement, functions can also be created by a function expression.

 For example, the function square could have been defined as:

 square = function(number) {
   
    return number * number 
    
    }

** Function expressions are convenient when passing a function as an argument to another function. The following example shows a map function that should receive a function as first argument and an array as second argument.**

*** Calling functions ***

Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.





