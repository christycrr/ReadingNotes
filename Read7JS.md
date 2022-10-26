the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:

if (isEmpty(field)) {
  promptUser();
} else {
  submitForm();
}
A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

Example
// Function to compute the product of p1 and p2
function myFunction(p1, p2) {
  return p1 * p2;
}
JavaScript Function Syntax
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
Function Return
When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The return value is "returned" back to the "caller":
Assign values to variables and add them together:

let x = 5;         // assign the value 5 to x
let y = 2;         // assign the value 2 to y
let z = x + y;     // assign the value 7 to z (5 + 2)
JavaScript Assignment Operators
Assignment operators assign values to JavaScript variables.

Operator	Example	Same As
=	x = y	x = y
+=	x += y	x = x + y
-=	x -= y	x = x - y
*=	x *= y	x = x * y
/=	x /= y	x = x / y
%=	x %= y	x = x % y
**=	x **= y	x = x ** y
Adding JavaScript Strings
The + operator can also be used to add (concatenate) strings.

Example
let text1 = "John";
let text2 = "Doe";
let text3 = text1 + " " + text2;
Adding two numbers, will return the sum, but adding a number and a string will return a string:

Example
let x = 5 + 5;
let y = "5" + 5;
let z = "Hello" + 5;
For example, the following code defines a simple function named square:

function square(number) {
  return number * number;
}
In JavaScript, a function can be defined based on a condition. For example, the following function definition defines myFunc only if num equals 0:

let myFunc;
if (num === 0) {
  myFunc = function (theObject) {
    theObject.make = 'Toyota';
  }
}
