# Day 6 exercises

## Chapter 3 Questions

####  If we have a function defined as `function sayHello(){console.log("Hello!")}`, what is the difference between entering `sayHello` and `sayHello()` in the console?

The parentheses after `sayHello` let the interpreter know that you are calling the function. By omitting the parentheses at the end, the console would simply repeat the function definition, instead of calling it.

####  What is the difference between function parameters and arguments?

Parameters are the values the function is requesting, arguments are the values that you are giving the function. A function is declared with two parameters, so the user must then input two arguments, one for each parameter.

#### What is the keyword `return` used for?

The `return` keyword returns a value to the code that called the function. A function ends with the `return` value, returning the defined value for the function. This is used to make a function that will perform a a calculation, data is input and the function outputs something else.

#### How are local variables better than global variables? Are there instances you can think of where you might want to use a variable that is globally scoped over local?

Local variables are only stored in memory while the function is running, while global variables are stored as long as the web page is loaded on the browser.  Local variables take up less memory as a result, helping with loading times.  Local variables also do not have to worry about naming conflicts since they are only used within the function.  Globally scoped variables are best used for things that are not likely to change and will be used by multiple functions.
