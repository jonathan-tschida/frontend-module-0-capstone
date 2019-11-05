## Chapter 2 questions

#### How do you declare a variable. What does the equals sign really mean in JavaScript? What is it called in JavaScript?

You declare a variable with the `var` keyword. The equals sign is an assignment operator that assigns values.

#### There are three big data types in JavaScript: numbers, strings, and booleans. Describe what each of them are.

Numbers are numeric data, they can be whole numbers or decimals positive or negative.  Strings are data that consists of letters and other characters, they can include number characters but those will not be treated as number data.  Booleans are binary data, either `true` or `false`, these are keywords that are used by javascript.

#### What are the six rules for naming variables? What are a few JavaScript reserved words that you should avoid using for variable names?

1. The name must begin with a letter `$` or `_` but cannot start with a letter
2. The name can contain letters, numbers, `$` or `_` but no dashes `-` or periods `.`
3. No keywords or reserved words may be used
4. Variables are case sensitive
5. The variable name should describe the kind of information being stored
6. Use camelCase if the variable has more than one word (`_` is also acceptable)

Examples of reserved words for variables would be `var` `true` `false` etc

#### How can an array be useful when dealing with multiple related values? How do you access/change a value in an array?

Arrays can be useful when you don't know how many items a list will contain. You can access an array with the array name followed by square brackets containing the index number of the item you want to access (starting with 0) you can change any value by using `=` to assign a new value.

Changing the value of the second item in an array named `friends` to `"Ross"` would look like this: `friends[1] = "Ross"`

#### What is the difference between an expression and a statement?

A statement is a single line of code that is an instruction for the script.  An expression is a statement that contains an operator.

#### What are three types of operators and how are they used?

- Arithmetic operators are used for math functions, like `+` `-` `*` and `/`
- Comparison operators compare two values and output true or false:`>` `<` `==` `===`
- String operators combine strings together using `+`
