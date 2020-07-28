**What is variable?**

In this lesson, we’ll learn what a variable is, how it can be created, and that the equal sign (=) is an "assignment" operator, not an "equal to" operator.

### Summary

**Variable** – A variable is a “named storage” for data. To create a variable in JavaScript, use the `let` keyword (there is also `const` and obsolete var). You can assign certain data to variable using the assignment operator `=`.

Command format:

`let <variable name> = value; `

This command calculates the value to which variable is subsequently assigned.
Example:
```
let a = 1;          // value 1 is assigned to variable a 
let b = 3.25;       // value 3.25 is assigned to variable b 
let user = 'Alice'; // value 'Alice' is assigned to variable user 
let age = 25;       // value 25 is assigned to variable age
let isAdult = true; // value true is assigned to variable isAdult 
let line = '';      //  empty string is assigned to variable line 
let numberOfCertificates = null; // value null is assigned to variable numberOfCertificates

```
A variable can be created without assigning a value to it.
Example:
```
let telNumber;
let a; 
let b;
let user; 
let age; 
let isAdult; 
let line; 
let numberOfCertificates;

```
To print the value of a variable in the console use the `command console.log();`.

Example:
```
let count = 34;     // value 34 is assigned to variable count 
console.log(count); // console output will be 34

let a = 1;          // value 1 is assigned to variable a
console.log(a);     // console output will be 1

let b = a + 3.25;    // value a + 3.25 is assigned to variable b
console.log(b);     // console output will be 4.25

let user = 'Alice'; // value 'Alice' is assigned to variable user
console.log(user);  // console output will be "Alice"

let isAdult = true;   // value true is assigned to variable isAdult
console.log(isAdult); // console output will be true
```
You can override variables created with the `let` keyword, that is you can assign a new value to the variable. When you assign a new value to a variable, you do not need to use the `let` keyword.

Example:
```
let num = 5;                   // value 5 is assigned to variable num
console.log(num);              // console output will be 5
num = num + 4;                 // variable num is increased by 4
console.log(num);              // console output will be 9

let str = 'Have a nice day!';  // value ‘Have a nice day!’ is assigned to variable str
str = 'Have a great day!';     // Variable str is changed  
console.log(str);              // console output will be "Have a great day!"

let areTesters = true;         // value true is assigned to variable areTesters
areTesters = false;            // Variable areTesters is changed 
console.log(areTesters);       // console output will be false

let multi = 20;                // value 20 is assigned to variable multi
multi = multi * 5;             // Variable multi is multiplied by 5
console.log(multi);            // console output will be 100
