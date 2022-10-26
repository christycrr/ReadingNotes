At a high level, an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.
As the examples above also illustrate, all complex expressions are joined by operators, such as = and +. In this section, we will introduce the following operators:

Assignment operators
Comparison operators
Arithmetic operators
Bitwise operators
Logical operators
BigInt operators
String operators
Conditional (ternary) operator
Comma operator
Unary operators
Relational operators
For example, the following code defines a simple function named square:

function square(number) {
  return number * number;
}
Copy to Clipboard
The function square takes one parameter, called number. The function consists of one statement that says to return the parameter of the function (that is, number) multiplied by itself. The statement return specifies the value returned by the function:

return number * number;
For example, the following code defines a simple function named square:
LOOPS

function square(number) {
  return number * number;
}
Copy to Clipboard
The function square takes one parameter, called number. The function consists of one statement that says to return the parameter of the function (that is, number) multiplied by itself. The statement return specifies the value returned by the function:

return number * number;
The statements for loops provided in JavaScript are:

for statement
do...while statement
while statement
labeled statement
break statement
continue statement
for...in statement
for...of statement
