<a name="top"></a>

# ![JavaScript Icon](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/JS-icon.png) JavaScript Simplified: An Efficient Learning Guide

![JavaScript Version](https://img.shields.io/badge/JavaScript-ES6-yellow)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)

A comprehensive yet concise quick-reference and overview of JavaScript fundamentals. Designed as both an efficient learning tool and a rapid reference. This guide bridges the gap between learning and practical application, making JavaScript more accessible.

[Back to README](https://github.com/george-GPT/JavaScript-Quick-Reference/blob/main/README.md)

## Introduction to JavaScript

- [1.1 Overview of JavaScript](#11-overview-of-javascript)
- [1.2 JavaScript Code Order](#12-javascript-code-order)

## Variables and Declarations

- [2.1 Understanding var, let, and const](#21-understanding-var-let-and-const)
- [2.2 Basic Data Types](#22-basic-data-types)
- [2.3 Syntax and Examples](#23-syntax-and-examples)
- [2.4 Operators](#24-operators)

## Fundamental Programming Concepts

- [3.1 Functions](#31-functions)
- [3.2 Loops](#32-loops)
- [3.3 Conditional Statements](#33-conditional-statements)
- [3.4 Arrays](#34-arrays)
- [3.5 Objects](#35-objects)
- [3.6 Error Handling](#36-error-handling)

## Global JavaScript Objects

- [4.1 String](#41-string)
- [4.2 Numbers](#42-numbers)
- [4.3 Math](#43-math)
- [4.4 Date](#44-date)

## DOM & DOM Manipulation

- [5.1 Understanding DOM & DOM Manipulation](#51-understanding-dom--dom-manipulation)
- [5.2 Accessing and Modifying DOM Elements](#52-accessing-and-modifying-dom-elements)
- [5.3 DOM Node Properties and Methods](#53-dom-node-properties-and-methods)
- [5.4 DOM Event Handling](#54-dom-event-handling)

## Asynchronous JavaScript

- [6.1 Asynchronous Operations in Javascript](#61-asynchronous-operations-in-javascript)
- [6.2 Callbacks](#62-callbacks)
- [6.3 Promises](#63-promises)
- [6.4 Asnyc/Await](#64-asyncawait)

## Working with APIs

- [7.1 Understanding APIs & JSON](#71-understanding-apis--json)
- [7.2 API Key Management](#72-api-key-management)
- [7.3 Making API Requests](#73-making-api-requests)
- [7.4 Handling JSON Data](#74-handling-json-data)

## Object-Oriented Programming (OOP)

- [8.1 Object-Oriented Programming (OOP)](#81-object-oriented-programming-oop)

## Building Projects with JavaScript

- [9.1 Using HTML Elements in JavaScript](#91-using-html-elements-in-javascript)
- [9.2 Choosing Between Objects and Arrays](#92-choosing-between-objects-and-arrays)
- [9.3 Managing User Input](#93-managing-user-input)
- [9.4 Form Validation](#94-form-validation)
- [9.5 Leveraging Randomness with Math.random()](#95-leveraging-randomness-with-mathrandom)
- [9.6 Persisting Data with Web Storage](#96-persisting-data-with-web-storage)
- [9.7 Coding Logic vs Data Retrieval & Execution](#97-coding-logic-vs-data-retrieval--execution)

## Tips and Best Practices

- [10.1 Tips and Best Practices](#101-tips-and-best-practices)

---

## 1.1 Overview of JavaScript

Explore the JavaScript language and its versatile capabilities, including:

- Being a high-level, interpreted programming language.
- Supporting dynamic typing for variables with varying data types.
- Embracing multiple programming paradigms: event-driven, functional, and imperative.

### ![JavaScript Core Features](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/cog.png) Core Features

Discover how JavaScript enhances user interaction on web pages by manipulating HTML and CSS. Learn how it handles asynchronous operations to make web applications more responsive.

### ![JavaScript and ECMAScript](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/js.png) JavaScript and ECMAScript

Understand JavaScript's adherence to ECMAScript (ES) standards, including significant updates introduced in ES6/ES2015, such as let/const, arrow functions, and classes.

### ![JavaScript Environments](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/stack.png) Environments

Explore JavaScript's versatility in both client-side (browser) and server-side (Node.js) development. See how it empowers the creation of dynamic web page content and back-end applications.

### ![JavaScript Role in Web Development](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/webdev.png) Role in Web Development

Understand JavaScript's integral role in web development, including its interactivity, DOM manipulation, and server-side capabilities.

### ![Integration with Web Technologies](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/tech.png) Integration with Web Technologies

Learn how JavaScript collaborates with HTML and CSS to deliver complete web page functionality. Discover its use of AJAX for asynchronous web tasks.

### ![JavaScript Libraries and Frameworks](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/react.png) Libraries and Frameworks

Explore libraries like React and frameworks like Angular, Vue.js, and Ember.js that simplify common tasks and provide robust tools for building complex applications.

## [🔝 Back to Top](#top)

## 1.2 JavaScript Code Order

The order of your code is vital for logical flow, efficient loading, and readability.

### ![JavaScript Libraries and Frameworks](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/question.png) Why It Matters

- **Logical Flow:** Ensures proper function sequencing.
- **Loading Efficiency:** Affects resource loading and page speed.
- **Readability:** Enhances code comprehension.
- **Maintainability:** Facilitates updates and bug fixes.
- **Collaboration:** Simplifies teamwork and code sharing.

### ![JavaScript Libraries and Frameworks](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/list.png) Code Order Variability

Optimal code order varies based on project needs and best practices:

- **Library/Framework Integration:** Follow library/framework guidelines (e.g., React prioritizes state and rendering).
- **Event-Driven Applications:** In event-driven apps (e.g., games or chat), focus on event handling and async tasks.
- **Complex Form Validation:** For intricate form validation, focus on form handling and validation early.
- **Performance Optimization:** Adjust the order for performance optimization as per your app's requirements.
- **Team Workflow:** Adapt to your team's workflow and code organization preferences when collaborating.

### ![JavaScript Libraries and Frameworks](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/list2.png) General JavaScript Order

General structure to use as a baseline:

1. **DOM References and Global Variables:** Declare and manage references to HTML elements and global variables.
2. **Modularization and Code Organization:** Organize code into modules and understand import/export for better maintainability.
3. **Function Definitions and Local Variables:** Define reusable functions and declare local variables within functions.
4. **Form Handling, Validation, and State Management:** Efficiently handle forms, validate user input, and manage application state.
5. **Responsive Design and DOM Manipulations:** Create responsive designs and interact with DOM elements.
6. **Event Listeners and Additional Initializations:** Attach event listeners and perform setup tasks.
7. **Asynchronous Operations and API Calls:** Handle asynchronous tasks and make API requests.
8. **Error Handling and Debugging:** Implement error handling and debugging techniques.
9. **Performance Optimization and Testing:** Optimize code for performance and introduce testing practices.

## [🔝 Back to Top](#top)

## 2.1 VARIABLES AND DECLARATIONS

Understanding variable declaration and scope in JavaScript.

- **'var':** Function-scoped variable declaration (uncommon in modern JS)

  - `var oldVar = "I am old";` Avoid using 'var' when possible

- **'let':** Block-scoped variable declaration (can be reassigned)

  - `let newLet = "I am new";` Preferred for variables that can change

- **'const':** Block-scoped and constant variable declaration (cannot be reassigned)
  - `const constantVar = "I am constant";` Use for variables that should not change

## [🔝 Back to Top](#top)

## 2.2 BASIC DATA TYPES

Overview of primitive data types in JavaScript.

- **Number:** Represents both integers and floats

  - `let score = 75;` Integer
  - `let price = 9.99;` Float

- **String:** Represents textual data

  - `let name = "Alice";`

- **Boolean:** Represents true or false values

  - `let isPassed = score > 50; `

- **Undefined:** Variable declared but not assigned

  - `let result;`

- **Null:** Explicitly signifies no value
  - `let data = null;`

## 2.3 SYNTAX AND EXAMPLES

Examples illustrating syntax for variable declarations and data types.

### Declaring Multiple Variables

`let x = 5, y = 10; // Multiple variables in one line`

### String Concatenation

`let greeting = "Hello " + name; // "Hello Alice"`

### Template Literals (ES6)

`` `let greetingTemplate = `Hello ${name}`; // "Hello Alice"` ``

### Arithmetic Operations

- `let sum = x + y;` Addition (15)
- `let diff = y - x;` Subtraction (5)

### Boolean Logic

`let isGreater = x > y;` false

### Type Coercion

`let total = "3" + 4;` "34", number 4 becomes a string

### The typeof Operator

The `typeof` operator is used to determine the type of a variable or expression. It returns a string indicating the data type.

```javascript
let num = 42;
console.log(typeof num); // Outputs: "number"

let str = 'Hello, world!';
console.log(typeof str); // Outputs: "string"

let bool = true;
console.log(typeof bool); // Outputs: "boolean"
```

## [🔝 Back to Top](#top)

## 2.4 Operators

Operators allow you to perform various tasks, such as assigning values to variables, comparing values, performing arithmetic operations, and more. This section provides an overview of the different types of operators in JavaScript.

### Assignment Operators

- `=` Assigns the value on the right to the variable on the left.
- `+=` Adds the value on the right to the variable on the left.
- `-=` Subtracts the value on the right from the variable on the left.
- `*=` Multiplies the variable on the left by the value on the right.
- `/=` Divides the variable on the left by the value on the right.

### Comparison Operators

`==` Checks if the values of two operands are equal.
`!=` Checks if the values of two operands are not equal.
`===` Checks if the values and types of two operands are equal.
`==` Checks if the values or types of two operands are not equal.
`>` Checks if the value of the left operand is greater than the value of the right operand.
`<` Checks if the value of the left operand is less than the value of the right operand.
`>=` Checks if the value of the left operand is greater than or equal to the value of the right operand.
`<=` Checks if the value of the left operand is less than or equal to the value of the right operand.

### Logical Operators

`&&` Returns true if both operands are true.
`||` Returns true if either of the operands is true.
`!` Returns true if the operand is false and false if the operand is true.

### Arithmetic Operators

`+` Adds two operands.
`-` Subtracts the second operand from the first operand.
`*` Multiplies two operands.
`/` Divides the first operand by the second operand.
`%` Returns the remainder when the first operand is divided by the second operand.

## [🔝 Back to Top](#top)

## 3.1 FUNCTIONS

In JavaScript, functions are fundamental building blocks, acting as callable objects to perform tasks or return values. They enhance code organization, reusability, and testability. This section delves into functions, covering declarations, parameters, and advanced concepts.

### Function Declarations

Define functions using the `function` keyword, specifying parameters within parentheses.

```javascript
function greet(name) {
  return `Hello, ${name}!`;
}
console.log(greet('Alice'));
```

Outputs "Hello, Alice!"

### Function Parameters and Arguments

Functions accept inputs called parameters, defined at declaration, and are placeholders for data passed during invocation, called arguments. Parameters are locally scoped within the function, allowing you to reference them even if they haven't been assigned outside. Additionally, you can reference external or existing parameters within the function body. Arguments, on the other hand, are the actual values passed to the function when it's called, allowing for dynamic operation based on the values provided.

```javascript
function add(a, b) {
  return a + b;
}
console.log(add(5, 3)); // Outputs 8
```

### Default Parameters (ES6)

ES6 allows default values for parameters, used when no argument is provided for that parameter.

```javascript
function say(message = 'Hi') {
  console.log(message);
}
`say();` // Outputs "Hi"
`say("Hello");`; // Outputs "Hello"
```

### Rest Parameters (ES6)

Rest parameters syntax (...) enables functions to accept an indefinite number of arguments as an array.

```javascript
function sumAll(...numbers) {
  return numbers.reduce((acc, num) => acc + num, 0);
}
console.log(sumAll(1, 2, 3));
```

Outputs 6

### Arrow Functions (ES6)

Arrow functions offer a concise syntax for writing functions, useful for short operations and as function arguments.

```javascript
const arrowFunction = (parameters) => expression;
```

```javascript
// Traditional function expression
function add(a, b) {
  return a + b;
}

// Arrow function expression
const addArrow = (a, b) => a + b;

console.log(add(2, 3)); // Output: 5
console.log(addArrow(2, 3)); // Output: 5
```

In this example, the arrow function addArrow accomplishes the same thing but with a more concise syntax. It omits the function keyword and uses the => arrow syntax to define the function.

### Function Expressions

Function expressions assign an anonymous function to a variable. They offer flexibility, allowing functions to be defined and passed as data. Within these function expressions, parameters can refer to both existing variables and parameters that have not been previously declared or defined. This allows for dynamic behavior based on the values passed to the function when it's invoked.

```javascript
const square = function (x) {
  return x * x;
};
console.log(square(4)); // Outputs 16
```

### IIFE (Immediately Invoked Function Expression)

IIFEs are functions that execute immediately upon definition, useful for initializing applications or namespaces.

```javascript
(function () {
  console.log('This function runs right away!');
})();
```

### Higher-Order Functions

These functions accept or return other functions, facilitating abstraction and composition in programming.

```javascript
function applyOperation(a, b, operation) {
  return operation(a, b);
}
`const result = applyOperation(4, 2, multiply);` // Using the multiply arrow function
`console.log(result);`; // Outputs 8
```

## [🔝 Back to Top](#top)

## 3.2 LOOPS

Loops enable repetitive execution of code, streamlining tasks like array traversal and conditional iterations.

### Choosing the Right Loop Structure

- **for loop** when you need to repeat a block of code for a known number of iterations, typically defined by a start condition, an end condition, and an increment.
- **while loop** when the number of iterations is uncertain, and you need to continue iterating as long as a specific condition remains true.
- **do...while loop** when you need to execute a block of code at least once before evaluating the loop condition for further iterations.
- **for...in loop** to iterate over all enumerable properties of an object, often useful for iterating through object keys and values.
- **for...of loop (ES6)** when iterating over iterable objects like arrays or strings, providing a simpler syntax without needing to deal with indexes or properties.

### for Loop

Repeatedly runs a block of code a certain number of times.

```javascript
for (let i = 0; i < 5; i++) {
  console.log(i); // Outputs: 0, 1, 2, 3, 4
}
```

### while Loop

Executes code as long as a specified condition is true.

```javascript
let j = 0;
while (j < 5) {
  console.log(j); // Outputs: 0, 1, 2, 3, 4
  j++;
}
```

### do...while Loop

Executes code once, then repeats the loop as long as the condition is true.

```javascript
let k = 0;
do {
  console.log(k); // Outputs: 0, 1, 2, 3, 4
  k++;
} while (k < 5);
```

### for...in Loop

Iterates over all enumerable properties of an object.

```javascript
const person = { name: 'Alice', age: 30 };
for (const key in person) {
  console.log(`${key}: ${person[key]}`); // Outputs: "name: Alice", "age: 30"
}
```

### for...of Loop (ES6)

Iterates over iterable objects like arrays, strings.

```javascript
const numbers = [1, 2, 3, 4, 5];
for (const number of numbers) {
  console.log(number); // Outputs: 1, 2, 3, 4, 5
}
```

### Array.forEach()

Executes a specified function for each element within an array. While it's not a traditional loop, it's closely related to the topic of array iteration.

```javascript
numbers.forEach((number) => {
  console.log(number); // Outputs: 1, 2, 3, 4, 5
});
```

## [🔝 Back to Top](#top)

## 3.3 CONDITIONAL STATEMENTS

Quick reference for using conditional logic in JavaScript.

### if Statement

Executes code block if condition is true.

```javascript
if (condition) {
  // Code to be executed if condition is true
}
```

### if...else Statement

Executes one code block if condition is true, another if false.

```javascript
if (condition) {
  // Code to be executed if condition is true
} else {
  // Code to be executed if condition is false
}
```

### if...else if...else Statement

Executes multiple conditions.

```javascript
if (condition1) {
  // Code if condition1 is true
} else if (condition2) {
  // Code if condition2 is true
} else {
  // Code if neither condition1 nor condition2 is true
}
```

### switch Statement

Switch statements provide a way to perform different actions based on different conditions. They allow you to evaluate an expression and execute code blocks based on the matching case. Switch statements offer a more concise alternative to multiple if...else statements when dealing with multiple conditions.

```javascript
switch (expression) {
  case value1:
    // Code block to execute if expression equals value1
    break;
  case value2:
    // Code block to execute if expression equals value2
    break;
  // Additional cases as needed
  default:
  // Code block to execute if expression doesn't match any case
}
```

```javascript
const day = 'Monday';

switch (day) {
  case 'Monday':
    console.log('Today is Monday');
    break;
  case 'Tuesday':
    console.log('Today is Tuesday');
    break;
  default:
    console.log("It's neither Monday nor Tuesday");
}
```

### Ternary Operator

The ternary operator is a concise way to write conditional statements in JavaScript. It takes three operands: a condition, an expression to execute if the condition is true, and an expression to execute if the condition is false.

```javascript
condition ? expression1 : expression2;
```

```javascript
const age = 20;
const status = age >= 18 ? 'adult' : 'minor';

console.log(status); // Outputs: 'adult' since age is greater than or equal to 18
```

## [🔝 Back to Top](#top)

## 3.4 ARRAYS

Detailed guide on JavaScript Arrays, covering array manipulation methods, iteration, and array-specific operations.

- Use arrays to store a list of items in an ordered manner, where each item can be accessed by its numerical index.
- Arrays are ideal for scenarios where you need to perform operations like looping through elements, as they provide methods for iteration and manipulation.

### Properties

- `array.length` Reflects the number of elements in an array.
- `array.prototype` Represents the prototype for the Array constructor and allows to add new properties and methods to all Array objects.

### Methods

- `array.from(arrayLike[, mapFn[, thisArg]])` Creates a new Array instance from an array-like or iterable object.
- `array.isArray(object)` Returns true if a variable is an array, if not false.
- `array.of("element1", "element2");` Creates a new Array instance with a variable number of arguments, regardless of number or type of the arguments.

### Mutator Methods

- `arr.copyWithin(target, start, end)` Copies a sequence of array elements within the array.
- `arr.fill(value, start, end)` Fills all the elements of an array from a start index to an end index with a static value.
- `arr.pop()` Removes the last element from an array and returns that element.
- `arr.flat()` Merges nested array into one single array.
- `arr.push("element1", "element2");` Adds one or more elements to the end of an array and returns the new length of the array.
- `arr.reverse()` Reverses the order of the elements of an array in place — the first becomes the last, and the last becomes the first.
- `arr.shift()` Removes the first element from an array and returns that element.
- `arr.sort()` Sorts the elements of an array in place and returns the array.
- `array.splice(start, deleteCount, element1, element2)` Adds and/or removes elements from an array.
- `arr.unShift("element1", "element2");` Adds one or more elements to the front of an array and returns the new length of the array.

### Example of .sort() & .filter()

```javascript
let numbers = [3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5];

let result = numbers
  .sort((a, b) => a - b) // Sort in ascending order
  .filter((number) => number > 3); // Filter numbers greater than 3

console.log(result); // [4, 4, 5, 5, 5, 6, 9]
```

### Accessor Methods

- `array.filter(callback[, thisArg])` Creates a new array containing elements that meet a specified condition defined by the provided callback function.
- `array.at(index)` Returns the element at the specified index in the array.
- `array.concat(value1, value2, array2)` Returns a new array comprised of this array joined with other array(s) and/or value(s).
- `array.includes(searchElement, fromIndex)` Determines whether an array contains a certain element, returning true or false as appropriate.
- `array.indexOf(searchElement[, fromIndex])` Returns the first (least) index of an element within the array equal to the specified value, or -1 if none is found.
- `array.join(separator)` Joins all elements of an array into a string.
- `array.lastIndexOf(searchElement, fromIndex)` Returns the last (greatest) index of an element within the array equal to the specified value, or -1 if none is found.
- `array.slice(begin, end)` Extracts a section of an array and returns a new array.
- `array.toString()` Returns a string representing the array and its elements.
  - Overrides the Object.prototype.toString() method.
- `array.toLocaleString(locales, options)` Returns a localized string representing the array and its elements.
  - Overrides the `Object.prototype.toLocaleString()` method.

### Example of array.slice(begin, end)

```javascript
// Suppose we have an array of months
const months = ['January', 'February', 'March', 'April', 'May', 'June', 'July'];

// We want to get only the spring months
const springMonths = months.slice(2, 5);

console.log(springMonths); // Output: ['March', 'April', 'May']
```

### Iterating Through Array Elements

When iterating through array elements, you can use the index notation `[i]` to access a specific element at index `i`:

```javascript
const array = [10, 20, 30, 40, 50];

for (let i = 0; i < array.length; i++) {
    console.log(array[i]); // Accesses the element at index i
}
```

### Iteration Methods

- `array.every(callback[, thisArg])` Returns true if every element in this array satisfies the provided testing function.
- `array.filter(callback[, thisArg])` Creates a new array with all of the elements of this array for which the provided filtering function returns true.
- `array.find(callback[, thisArg])` Returns the found value in the array, if an element in the array satisfies the provided testing function or undefined if not found.
- `array.findIndex(callback[, thisArg])` Returns the found index in the array, if an element in the array satisfies the provided testing function or -1 if not found.
- `array.forEach(callback[, thisArg])` Calls a function for each element in the array.
- `array.keys()` Returns a new Array Iterator that contains the keys for each index in the array.
- `array.map(callback[, initialValue])` Creates a new array with the results of calling a provided function on every element in this array.
- `array.reduce(callback[, initialValue])` Apply a function against an accumulator and each value of the array (from left-to-right) as to reduce it to a single value.
- `array.reduceRight(callback[, initialValue])` Apply a function against an accumulator and each value of the array (from right-to-left) as to reduce it to a single value.
- `array.some(callback[, initialValue])` Returns true if at least one element in this array satisfies the provided testing function.
- `array.values()` Returns a new Array Iterator object that contains the values for each index in the array.


### Array.forEach()

Executes a specified function for each element within an array. While it's not a traditional loop, it's closely related to the topic of array iteration.

```javascript
numbers.forEach((number) => {
  console.log(number); // Outputs: 1, 2, 3, 4, 5
});
```

### array.reduce(callback[, initialValue])

```javascript
// Suppose we have an array of numbers
const numbers = [1, 2, 3, 4, 5];

// We want to find the sum of all numbers in the array
const sum = numbers.reduce((accumulator, currentValue) => {
  return accumulator + currentValue;
}, 0); // 0 is the initial value

console.log(sum); // Output: 15
```

### Array.includes() method

The includes() method in JavaScript is used to determine whether an array includes a certain value among its elements. It returns true if the array contains the specified element, and false otherwise. This method offers a simple way to check for the presence of a value within an array without needing to iterate through its elements manually.

```javascript
array.includes(searchElement, fromIndex);
```

```javascript
const fruits = ['apple', 'banana', 'orange', 'grape'];
console.log(fruits.includes('banana')); // Output: true
console.log(fruits.includes('watermelon')); // Output: false
```

## [🔝 Back to Top](#top)

## 3.5 OBJECTS

Objects are a collection of properties, where a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method.

- Objects are used to store data as key-value pairs, allowing for the organization of data with named properties that can be accessed using keys.
- They are suitable for representing more complex data structures where each item may contain a different set of properties.

### What is a Key?

It is a unique identifier used to access the corresponding value in the object. Keys are often strings (but can be symbols in ES6 and beyond), representing property names.

### What is a Value?

It is the data associated with a key within an object. Values can be of any data type, such as numbers, strings, arrays, functions, or even other objects.

### what is a Key Value Pair?

Together, a key and its associated value form a key-value pair, allowing you to store and organize data in a structured way within an object. For example, in the following object,"name" and "age" are keys, while "John" and 30 are their corresponding values:

```javascript
{ name: "John", age: 30 },
```

### Creating an Object

- `const myObject = { key1: 'value1', key2: 'value2' };` Object literal with two properties
- `Object.create()` creates a new object with a specified prototype object and properties

### Accessing Properties

In JavaScript, objects are collections of properties, and you can access these properties using either dot notation or bracket notation.

- `console.log(myObject.key1);` 'value1'
- `console.log(myObject['key2']);` 'value2'

### Dot Notation VS Bracket Notation

Dot notation is preferred for direct and straightforward property access when the property name is known at development time and is a valid JavaScript identifier. On the other hand, bracket notation offers more flexibility and versatility, allowing for dynamic property access, handling special cases, and enabling programmatic property access.

#### When to Use Dot Notation

- **Known Property Names:** Use dot notation when you know the property name at development time and it is a valid JavaScript identifier.
- **Clear and Direct Access:** Dot notation is ideal for accessing properties directly and offers a concise syntax for this purpose.
- **Code Readability:** It enhances code readability, especially when accessing well-known properties of objects.

#### When to Use Bracket Notation

- **Dynamic Property Access:** Use bracket notation when the property name is determined dynamically at runtime, such as when it's stored in a variable or computed through an expression.
- **Handling Special Cases:** Bracket notation is essential for accessing properties with special characters, spaces, or reserved words in JavaScript.
- **Programmatic Property Access:** It enables programmatic approaches to property access, making it useful for working with data structures, APIs, or situations where property names may vary.

### Adding Properties

- `myObject.key3 = 'value3';` Adding a new property 'key3'

### Deleting Properties

- `delete myObject.key2;` Removing property 'key2'

### Methods

A method in a JavaScript object is a property of the object that is a function. Methods are functions stored as object properties, and they are typically used to define actions or behavior for the object.

### Structure for Creating and Using Methods

```javascript
const exampleObject = {
  property1: 'Value1',
  property2: 'Value2',
  method1: function () {
    return 'Method1 returns: ' + this.property1;
  },
  method2: function (parameter) {
    console.log(
      'Method2 uses ' + parameter + ' and property2: ' + this.property2
    );
  },
};

console.log(exampleObject.method1()); // Calls method1, outputs: Method1 returns: Value1
exampleObject.method2('Parameter1'); // Calls method2 with "Parameter1" as an argument, outputs: Method2 uses Parameter1 and property2: Value2
```

### Example of Creating and Using Methods

```javascript
const person = {
  firstName: 'John',
  lastName: 'Doe',
  fullName: function () {
    return this.firstName + ' ' + this.lastName;
  },
  greet: function (greeting) {
    console.log(greeting + ', my name is ' + this.firstName);
  },
};

console.log(person.fullName()); // Calls the fullName method, outputs: John Doe
person.greet('Hello'); // Calls the greet method with "Hello" as an argument, outputs: Hello, my name is John
```

### Methods of the Object Constructor

Methods of the Object constructor in JavaScript provide a set of utility functions for creating, manipulating, and working with objects, including methods for object creation, property manipulation, and property enumeration.

- `Object.assign(target, ...sources)` Copies values from source to target objects.
- `Object.create(proto, propertiesObject)` Creates a new object with the specified prototype and properties.
- `Object.defineProperty(obj, prop, descriptor)` Defines a new property on an object.
- `Object.defineProperties(obj, props)` Defines multiple properties on an object.
- `Object.entries(obj)` Returns an array of a given object's own enumerable string [key, value] pairs.
- `Object.freeze(obj)` Freezes an object, preventing new properties and changes to existing properties.
- `Object.getOwnPropertyDescriptor(obj, prop)` Gets the descriptor for a property.
- `Object.getOwnPropertyDescriptors(obj)` Gets all own property descriptors of an object.
- `Object.getOwnPropertyNames(obj)` Returns an array of all properties (enumerable or not).
- `Object.getOwnPropertySymbols(obj)` Returns an array of all symbol properties.
- `Object.getPrototypeOf(obj)` Returns the prototype of the object.
- `Object.is(value1, value2)` Compares if two values are the same.
- `Object.isExtensible(obj)` Checks if an object can be extended with new properties.
- `Object.isFrozen(obj)` Checks if an object is frozen.
- `Object.isSealed(obj)` Checks if an object is sealed.
- `Object.keys(obj)` Returns an array of a given object's own enumerable properties.
- `Object.preventExtensions(obj)` Prevents any extensions of an object.
- `Object.seal(obj)` Prevents other code from deleting properties of an object.
- `Object.setPrototypeOf(obj, prototype)` Sets the prototype (i.e., the internal [[Prototype]] property).
- `Object.values(obj)` Returns an array of a given object's own enumerable property values.

### Example of object.assign()

```javascript
// Create a target object
const target = {
  name: 'John',
  age: 30,
};

// Create source objects
const source1 = {
  age: 25,
  profession: 'Engineer',
};

const source2 = {
  city: 'New York',
  hobby: 'Guitar',
};

// Use Object.assign to copy values from sources to the target
Object.assign(target, source1, source2);

// Display the modified target object
console.log(target);
```

### Looping Through Properties Using for...in

for...in loops through an object's properties to access and work with each property and its associated value.

```javascript
for (const key in myObject) {
  console.log(key, myObject[key]); // Logs key and value of each property
}
```

## [🔝 Back to Top](#top)

## 3.6 ERROR HANDLING

Overview of error handling mechanisms in JavaScript.

### try...catch Statement

Handles exceptions by testing a block of code for errors.

```javascript
try {
  // Code that may throw an error
} catch (error) {
  console.log(error); // Handling the error
}
```

### try...catch...finally Statement

Includes a block that runs regardless of the result.

```javascript
try {
  // Code that may throw an error
} catch (error) {
  console.log(error); // Handling the error
} finally {
  // Code that will run regardless of try / catch outcome
}
```

### throw Statement

Creates a custom error.

```javascript
function checkNumber(num) {
  if (isNaN(num)) {
    throw new Error('Input is not a number'); // Custom error
  }
}
```

### Example Usage of throw

```javascript
try {
  checkNumber('A');
} catch (e) {
  console.log(e.message); // Output: Input is not a number
}
```

## [🔝 Back to Top](#top)

## 4.1 STRINGS

Overview of commonly used methods of the String object.

### Properties

- `str.length` Returns the length of the string.
- `str.[index]` Allows you to access characters in the string using bracket notation

### Methods

- `str.charAt(index)` Returns the character at the specified index.
- `str.charCodeAt(index)` Returns an integer between 0 and 65535 representing the UTF-16 code unit at the given index.
- `str.concat(string2, string3[, ..., stringN])` Concatenates the string arguments to the calling string and returns a new string.
- `str.includes(searchString, position)` Determines whether one string may be found within another string, returning true or false.
- `str.indexOf(searchValue[, fromIndex])` Returns the index within the calling String object of the first occurrence of the specified value, or -1 if not found.
- `str.lastIndexOf(searchValue[, fromIndex])` Returns the index within the calling String object of the last occurrence of the specified value, or -1 if not found.
- `str.match(regexp)` Used to match a regular expression against a string.
- `str.repeat(count)` Constructs and returns a new string which contains the specified number of copies of the string on which it was called, concatenated together.
- `str.replace(searchFor, replaceWith)` Used to find a match between a regular expression and a string, and to replace the matched substring with a new substring.
- `str.search(regexp)` Executes a search for a match between a regular expression and this String object.
- `str.split(separator[, limit])` Splits a String object into an array of strings by separating the string into substrings.
- `str.substr(start[, length])` Returns the characters in a string beginning at the specified location through the specified number of characters.
- `str.substring(indexStart[, indexEnd])` Returns a new string containing the specified part of the given string.
- `str.toLowerCase()` Returns the calling string value converted to lowercase.
- `str.toUpperCase()` Returns the calling string value converted to uppercase.
- `str.trim()` Trims whitespace from the beginning and end of the string.
- `str.valueOf()` Returns the primitive value of a String object.

### String Interpolation (Template Literals)

- `const name = "Alice";`
- `` `const greeting = `Hello, ${name}!`;` `` Hello, Alice!

### Multi-line Strings using Template Literals

```javascript
const multiLineString = `This is a string
that spans across
multiple lines`;
console.log(multiLineString);
```

## [🔝 Back to Top](#top)

## 4.2 NUMBERS

Fundamental number-related functionalities in JavaScript.

### What is an Integer?

An integer is a whole number without any fractional or decimal parts, such as -1, 0, or 42. It's used in scenarios requiring countable quantities, like loop counters, array indexes, or any situation where partial values don't make sense.

### What is a Floating-Point Number?

A floating-point number includes decimal parts, allowing for the representation of fractions and precise measurements, like 3.14 or -0.01. Useful in calculations requiring high precision, such as financial transactions, scientific computations, or any scenario where small, incremental values matter.

### parseInt(string, radix)

- `parseInt("10", 10);` Converts the string "10" to an integer (base 10).
- `parseInt("10", 2);` Converts the string "10" to an integer (base 2, binary).

### parseInt Example

```javascript
// Sample input from the user
const userInput = '42';

// Using parseInt to convert the string to an integer
const parsedNumber = parseInt(userInput);

// Checking if the conversion was successful
if (!isNaN(parsedNumber)) {
  console.log(`Parsed number: ${parsedNumber}`);
  console.log(`Type of parsedNumber: ${typeof parsedNumber}`);
} else {
  console.log('Conversion failed. Please enter a valid number.');
}
```

### parseFloat(string)

`parseFloat("3.14");` Converts the string "3.14" to a floating-point number.

### toFixed(digits)

```javascript
const num = 123.456;
num.toFixed(2); // Returns "123.46" - formats the number using fixed-point notation.
```

### Array Destructuring

```javascript
const fruits = ['Apple', 'Banana', 'Cherry'];
const [firstFruit, secondFruit] = fruits;
console.log(firstFruit); // 'Apple'
console.log(secondFruit); // 'Banana'
```

### Spread Operator in Arrays

```javascript
const primeNumbers = [2, 3, 5];
const morePrimes = [7, ...primeNumbers, 11];
console.log(morePrimes); // [7, 2, 3, 5, 11]
```

### Additional Number Properties and Methods

- `Number.isFinite(1000);` true
- `Number.isNaN(NaN);` true
- `Number.isInteger(10);` true
- `Number.isSafeInteger(10);` true
- `Number.MAX_VALUE;` The largest positive representable number
- `Number.MIN_VALUE;` The smallest positive representable number

## [🔝 Back to Top](#top)

## 4.3 MATH

Essential guide to JavaScript's Math object, covering basic constants and mathematical functions.

### Math Constants

- `Math.PI; π:` Approximately 3.14159
- `Math.E; Euler's constant, e:` Approximately 2.718

### Basic Math Methods

- `Math.abs(-5);` Absolute value: Returns 5
- `Math.ceil(4.2);` Ceiling: Rounds up to 5
- `Math.floor(4.8);` Floor: Rounds down to 4
- `Math.round(4.5);` Round: Rounds to 5
- `Math.max(1, 3, 5);` Maximum value: Returns 5
- `Math.min(1, 3, 5);` Minimum value: Returns 1

### Exponential and Logarithmic Functions

- `Math.exp(1);` e^1: Returns Euler's number raised to the power of 1
- `Math.log(10);` Natural logarithm of 10

### Trigonometric Functions (Basic)

- `Math.sin(0)` Sine: Returns 0 (sin of 0 degrees)
- `Math.cos(Math.PI);` Cosine: Returns -1 (cos of 180 degrees)

### Power and Square Root Functions

- `Math.pow(2, 3);` 2 to the power of 3: Returns 8
- `Math.sqrt(16);` Square root of 16: Returns 4

### Random Number Generation

- `Math.random();` Generates a random number between 0 (inclusive) and 1 (exclusive)

### Example of Math.random() to generate a random choice

```javascript
// Function to get a random choice for the computer
function getComputerChoice() {
  const randomNumber = Math.random(); // Generates a random number between 0 (inclusive) and 1 (exclusive).

  if (randomNumber < 1 / 3) {
    return 'rock';
  } else if (randomNumber < 2 / 3) {
    return 'paper';
  } else {
    return 'scissors';
  }
}

// Example usage:
const computerSelection = getComputerChoice();
console.log(`Computer chose: ${computerSelection}`);
```

### Math.trunc

Math.trunc is a method in JavaScript's Math object that is used to remove the decimal part of a number, effectively truncating it to an integer. This method does not round the number; it simply cuts off the decimal portion.

### How Math.trunc Fits With Math.random

The combination of Math.trunc and Math.random is particularly useful when you need to generate random integers within a specific range. Math.random generates the random decimal number, and Math.trunc can be used to truncate this number to an integer.

- Keep in mind that Math.random() generates a number starting from 0, to start from 1 we add +1 to the end of the equation.

```javascript
let randomInteger = Math.trunc(Math.random() * 10) + 1;
```

## [🔝 Back to Top](#top)

## 4.4 DATES

Introduction to JavaScript's Date object, focusing on creating, manipulating, and formatting dates.

### Creating Date Objects

- `const now = new Date();` Current date and time
- `const specificDate = new Date('2024-01-24');` Specific date (YYYY-MM-DD)
- `const specificDateTime = new Date('2024-01-24T12:00:00');` Specific date and time (YYYY-MM-DDTHH:MM:SS)

### Date Methods

- `now.getFullYear();` Get the year as a four digit number (yyyy)
- `now.getMonth();` Get the month as a zero-based value (0-11)
- `now.getDate();` Get the day as a number (1-31)
- `now.getDay();` Get the weekday as a number (0-6)
- `now.getHours();` Get the hour (0-23)
- `now.getMinutes();` Get the minute (0-59)
- `now.getSeconds();` Get the second (0-59)
- `now.getMilliseconds();` Get the milliseconds (0-999)
- `now.getTime();` Get the time (milliseconds since January 1, 1970)

### Setting Date Values

- `now.setFullYear(2024);` Set the year (optionally month, day)
- `now.setMonth(0);` Set the month (0-11)
- `now.setDate(24);` Set the day as a number (1-31)
- `now.setHours(12);` Set the hour (0-23)
- `now.setMinutes(30);` Set the minute (-59)
- `now.setSeconds(30);` Set the second (0-59)
- `now.setMilliseconds(123);` Set the milliseconds (0-999)

### Formatting Dates

- `now.toDateString();` Converts the date portion to a readable string
- `now.toTimeString();` Converts the time portion to a readable string
- `now.toLocaleDateString();` Returns the date portion in a locale-sensitive format
- `now.toLocaleTimeString();` Returns the time portion in a locale-sensitive format
- `now.toISOString();` Returns the date in ISO format (YYYY-MM-DDTHH:MM:SS.sssZ)

### Comparing Dates

- `const earlier = new Date('2024-01-01');`
- `const later = new Date('2024-12-31');`
- `const isLater = later > earlier;` true if 'later' is a later date than 'earlier'

## [🔝 Back to Top](#top)

## 5.1 Understanding DOM & DOM Manipulation

The DOM (Document Object Model) is a JavaScript programming interface for web documents. It represents web pages as a tree of nodes and objects, allowing you to change their structure, style, and content.

### The DOM Basics

- **Introduction to the DOM**: The DOM is a way to interact with web documents using JavaScript. It represents the page as a tree, enabling you to modify its content and structure.

- **window Object**: The `window` object represents the browser window and provides functions and properties for window control and event handling.

- **document Object**: The `document` object represents the web page's content. It allows JavaScript to add, modify, and interact with elements on the page.

### Dom Manipulation Process

To manipulate the DOM, you begin by selecting the desired DOM element(s) using methods like getElementById, querySelector, or getElementsByClassName. Once you've selected the element(s), you can directly apply modifications, such as changing content or styling. While it's common to assign elements to variables for convenience and reusability, it's not mandatory. You can select elements and perform modifications without the need for intermediate variable declarations.

### Example: Basic interaction with the DOM using JavaScript

```javascript
// Access an element by its ID
const element = document.getElementById('example-element');

// Modify the element's content
element.innerHTML = 'This is the new content.';

// This updates the HTML content of the element.
```

## [🔝 Back to Top](#top)

## 5.2 ACCESSING AND MODIFYING DOM ELEMENTS

Methods for selecting, creating, and modifying DOM elements.

### Primary Methods of Accessing Elements

- `document.getElementById(id);` Gets an element by its ID.
- `document.querySelector(selector);` Returns the first element matching the specified CSS selector.
- `document.querySelectorAll(selector);` Returns a NodeList of all elements matching the specified CSS selector.

## Other Methods of Accessing elements

- `document.getElementsByTagName(name);` Returns a live HTMLCollection of elements with the given tag name.
- `document.getElementsByClassName(className);` Returns a live HTMLCollection of elements with the given class name.

### Creating and Inserting Elements

- `const newElement = document.createElement(tagName);` Creates a new element with the specified tag name.
- `element.appendChild(newElement);` Appends the new element as the last child of the parent element.

### Removing Elements

- `element.removeChild(child);` Removes a child node from the DOM.

### Modifying Elements

- `element.innerHTML = '<p>New HTML content</p>';` Changes the HTML content of an element.
- `element.textContent = 'New text content';` Changes the text content of an element.
- `element.setAttribute(name, value);` Sets a new value for an attribute on the element.
- `element.getAttribute(attributeName);` Gets the current value of an attribute on the element.
- `element.removeAttribute(attributeName);` Removes an attribute from the element.
- `element.classList.add(className);` Adds a class to the element.
- `element.classList.remove(className);` Removes a class from the element.
- `element.classList.toggle(className);` Toggles a class on the element.
- `element.style.property = "value";` Changes the style of an element.

### Examples of Common Style Properties & Attributes

- `element.style.color = "red";` Sets the text color of the element.
- `element.style.backgroundColor = "yellow";` Sets the background color of the element.
- `element.style.border = "1px solid black";` Sets a border for the element.
- `element.style.marginTop = "10px";` Sets the top margin of the element.
- `element.style.paddingLeft = "20px";` Sets the left padding of the element.
- `element.style.opacity = "0.8";` Adjusts element opacity.
- `element.style.boxShadow = "2px 2px 5px #888888";` Adds a box shadow.
- `element.style.transform = "rotate(45deg)";` Applies a rotation transform.
- `element.style.transition = "all 0.3s ease-in-out";` Sets transition effects.
- `element.style.zIndex = "100";` Controls the stacking order.
- `element.hidden = true;` Hides the element.
- `element.disabled = true;` Disables the element.

### Cloning Elements

`const clone = element.cloneNode(true); ` Clones the element and its descendants.

## [🔝 Back to Top](#top)

## 5.3 DOM NODE PROPERTIES AND METHODS

Overview of properties and methods specific to DOM nodes.

### Node Properties

- `node.childNodes;` A live NodeList containing all the children of this node.
- `node.firstChild;` The node's first child in the tree, or null if the node has no children.
- `node.lastChild;` The node's last child in the tree, or null if the node has no children.
- `node.nextSibling;` The node immediately following this node, or null if there's no sibling node.
- `node.nodeName;` The name of the node, depending on its type.
- `node.nodeType;` A code representing the type of the node (e.g., 1 for Element nodes, 3 for Text nodes).
- `node.nodeValue;` The value of the current node (varies depending on the node type).
- `node.parentNode;` The parent of the node, or null if it has no parent.
- `node.previousSibling;` The node immediately preceding this node, or null if there's no sibling.

### Node Methods

- `node.cloneNode(deep);` Clones the node. If 'deep' is true, it clones all descendants, otherwise it clones only the node.
- `node.contains(otherNode);` Returns true if 'otherNode' is a descendant of the node, false otherwise.
- `node.hasChildNodes();` Returns true if the node has any children, false otherwise.
- `node.insertBefore(newNode, referenceNode);` Inserts 'newNode' before the 'referenceNode' as a child of the current node.
- `node.replaceChild(newChild, oldChild);` Replaces 'oldChild' with 'newChild' among the children of the node.

### Example Usage

```javascript
const list = document.getElementById('myList');

// Get the text content of the first child node
const firstChildText = list.firstChild.innerText;

// Change the HTML content of the list
list.innerHTML = '<li>New Item 1</li><li>New Item 2</li>';

// Create a new list item element
const newItem = document.createElement('li');
newItem.innerText = 'New Item 3';

// Insert the new item at the beginning of the list
list.insertBefore(newItem, list.firstChild);
```

## [🔝 Back to Top](#top)

## 5.4 DOM EVENT HANDLING

Methods for attaching, handling, and removing event listeners on DOM elements.

### Adding Event Listeners

### Anonymous Function Event Listener

For simple, one-time event handling without the need for additional checks or complex logic:

```javascript
document.getElementById('myButton').addEventListener('click', function () {
  handleButtonClick();
});
```

### Named Function Event Listener

For additional checks, complex logic, or reusability, using a named function offers better code organization and maintainability:

```javascript
document
  .getElementById('myButton')
  .addEventListener('click', buttonClickFunction);
```

### DOMContentLoaded Event Listener

To execute code when the DOM is fully loaded and parsed, use the DOMContentLoaded event.

```javascript
document.addEventListener('DOMContentLoaded', function () {});
```

### Removing Event Listeners

- `elementName.removeEventListener("click", buttonClickFunction);`

### Event Propagation: Capturing and Bubbling

- **Capturing:** Events propagate from the window down to the target's ancestors.
- **Bubbling:** Events propagate from the target up to the window.

### Stopping Event Propagation

```javascript
function eventHandler(event) {
  event.stopPropagation(); // Prevents further propagation of the current event.
}
```

### Preventing Default Event Behavior

```javascript
element.addEventListener('click', function (event) {
  event.preventDefault(); // Cancels the event if it is cancelable, without stopping its propagation.
});
```

### Common Event Types

- **Mouse Events:** `'click', 'dblclick', 'mousedown', 'mouseup', 'mousemove', 'mouseover', 'mouseout', 'mouseenter', 'mouseleave'`
- **Keyboard Events:** `'keydown', 'keypress', 'keyup'`
- **Form Events:** `'submit', 'change', 'focus', 'blur'`
- **Window Events:** `'load', 'resize', 'scroll', 'unload', 'error'`

### Example of a keydown event

```javascript
document.addEventListener('keydown', function (event) {
  if (event.key === 'Enter') {
    // Call your function here
    // Example: handleEnterKey();
  }
});
```

## [🔝 Back to Top](#top)

## 6.1 ASYNCHRONOUS OPERATIONS IN JAVASCRIPT

This section covers JavaScript's asynchronous operations, including network requests and user interactions.

### What Are Asynchronous Operations?

Asynchronous operations are tasks that occur independently of the main program flow. They often involve actions like fetching data from a remote server, reading files, or waiting for user interactions. These tasks can take time to complete, and they may not block the execution of other parts of your program.

### Common Approaches

There are several approaches for handling asynchronous operations in JavaScript:

- **Callbacks (Traditional Approach):** Callbacks are a common way to manage asynchronous tasks. They involve passing a function as an argument to another function to execute when the asynchronous operation is complete.

- **Promises (Structured Approach):** Promises provide a more structured way to handle asynchronous operations. They represent a value that may be available now or in the future, allowing you to perform actions once the operation completes.

- **Async/Await (Modern Approach):** Async/await is a set of JavaScript keywords that simplifies working with promises. It allows you to write asynchronous code that resembles synchronous code, improving code readability and maintainability.

## [🔝 Back to Top](#top)

## 6.2 CALLBACKS

A callback is a function passed as an argument to another function, executed once a specific task is complete.
While useful in certain scenarios, callbacks have limitations, particularly in complex code with error handling.

### When to Consider Using Callbacks

Callbacks are commonly used in the following situations:

- Handling asynchronous operations, like fetching data from a server.
- Managing event-driven programming, such as user interactions or timers.
- Dealing with I/O operations, like reading files in Node.js.

While callbacks can be employed in these scenarios, they may not always be the most efficient or maintainable choice.
In more complex applications, Promises or async/await can provide a more structured and readable approach.

### Potential Downsides of Callbacks

- **Callback Hell**: In complex applications with multiple nested callbacks, code readability can suffer, leading to a pattern known as "Callback Hell" or "Pyramid of Doom."

- **Limited Error Handling**: Error handling can be more challenging with callbacks, often requiring the passing of error parameters to handle errors effectively.

### Example: Fetching Data from a Server

```javascript
// Simulated asynchronous data fetching
function fetchDataFromServer(callback) {
  // Simulate a network request delay
  setTimeout(() => {
    const responseData = { message: 'Data from the server' };
    callback(responseData);
  }, 2000); // Simulated 2-second delay
}

// Callback function to handle the fetched data
function handleFetchedData(data) {
  console.log('Received data:', data.message);
}

// Usage: Fetch data from the server and handle it with the callback
fetchDataFromServer(handleFetchedData);
```

## [🔝 Back to Top](#top)

## 6.3 PROMISES

Promises are a crucial part of JavaScript for handling asynchronous operations in a structured and organized manner.

### What Are Promises?

Promises are a structured way to manage asynchronous operations in JavaScript. They represent a value that can become available now or in the future, allowing you to take action once the operation finishes.

Promises offer a clear separation between initiating an asynchronous task and dealing with its outcome or errors. They provide a standardized approach to asynchronous code, improving code clarity and maintainability.

**Note**: Promises have a capital first letter, unlike most JavaScript syntax.

### Key Concepts of Promises

To understand promises fully, consider these key concepts:

- **Creation**: You can create a promise using the `Promise` constructor, encapsulating an asynchronous task.

- **States**: Promises have three states: pending, resolved (fulfilled), and rejected. They transition from pending to either resolved or rejected based on the outcome of the asynchronous task.

- **Handling**: Promises offer methods like `then()` and `catch()` to handle the result or errors once the promise settles.

- **Chaining**: Promises allow you to chain multiple asynchronous operations together, making it easy to sequence tasks.

### Example: Creating and Consuming a Promise

```javascript
// Simulated asynchronous data fetching using a Promise
function fetchDataFromServer() {
  return new Promise((resolve, reject) => {
    // Simulate a network request delay
    setTimeout(() => {
      const responseData = { message: 'Data from the server' };
      resolve(responseData); // Resolve the Promise with the fetched data
    }, 2000); // Simulated 2-second delay
  });
}
// Usage: Fetch data from the server using the Promise
fetchDataFromServer()
  .then((data) => {
    console.log('Received data:', data.message);
  })
  .catch((error) => {
    console.error('Error:', error);
  });
```

## [🔝 Back to Top](#top)

## 6.4 ASYNC/AWAIT

Async/await simplifies the process of working with promises and is widely adopted in modern JavaScript development.

### What is async/await?

async/await is a set of JavaScript keywords that simplifies the process of working with promises, allowing you to write asynchronous code that resembles synchronous code, improving code readability and maintainability.

### Benefits of async/await

- **Simplicity**: async/await reduces the complexity of handling promises, resulting in more concise and readable code.
- **Error Handling**: It simplifies error handling with try...catch blocks, improving code reliability.
- **Sequencing**: async/await allows you to sequence asynchronous tasks in a natural order, enhancing code flow.

### Using asnyc/await to Fetch Data From a Server

```javascript
async function fetchData() {
  try {
    const response = await fetch('https://api.example.com/data');
    const data = await response.json();
    return data;
  } catch (error) {
    throw an Error('Failed to fetch data');
  }
}
```

### Consuming Data Using the async Function

```javascript
fetchData()
  .then((data) => {
    console.log(data); // Handle the fetched data
  })
  .catch((error) => {
    console.error(error.message); // Handle errors
  });
```

## [🔝 Back to Top](#top)

## 7.1 UNDERSTANDING APIs & JSON

Exploring the fundamentals of APIs, JSON and the importance of API keys in web development.

### APIs at a Glance

APIs (Application Programming Interfaces) connect your code to external services for data and functions.

### API Keys

For many APIs, you'll need an API key for authentication and usage tracking:

1. **Sign Up:** Create an account on the API provider's website.
2. **Generate Key:** In your account settings, generate an API key.
3. **Usage Guidelines:** Check the provider's documentation for usage instructions, rate limits, and any costs.

### JSON Simplified

JSON (JavaScript Object Notation) is a straightforward, human-readable data format commonly used in APIs for data exchange.

### Handling JSON

When working with JSON data, remember to:

- **Parse:** Convert JSON to JavaScript objects.
- **Access:** Find specific information within the structure.
- **Modify:** Adjust data as needed.
- **Stringify:** Convert JavaScript objects back to JSON for storage or transmission.

## [🔝 Back to Top](#top)

## 7.2 API Key Management

API Key Management involves securely storing keys server-side and regulating their use to prevent unauthorized access, crucial for protecting applications from security breaches.

### API Key Management: Educational Examples vs. Real-World Application

This guide displays code examples of API requests that don't use API key management for learning ease. Securing API keys is more advanced, requiring additional tools and knowledge in server-side development. However, secure management is vital in real-world applications for data security and integrity.

### When It's important to follow API Key Management

- **Production Environments:** Exposing API keys can lead to unauthorized access and potential data breaches.

- **Handling Sensitive Data:** When dealing with personal, financial, or confidential information, securing API keys is essential to prevent data theft and service abuse.

- **Rate Limits and Costs:** Exposed keys can be misused, leading to rate limit breaches and unexpected costs.

### Securing API Keys - Advanced Approach

- **Environment Variables**: Use server-side environment variables for API keys. Tools like dotenv in Node.js can help manage these.

- **Server-Side Requests:** Process API requests on the server. This requires setting up a server environment (Node.js, Python, etc.) and understanding server-side programming.

- **Access Control:** Utilize API provider's settings to limit key usage by IP, referer URL, or application.

- **Rate Limiting and Monitoring:** Apply rate limiting and monitor API key usage to detect unauthorized access. This may involve additional monitoring tools or services.

## [🔝 Back to Top](#top)

## 7.3 MAKING API REQUESTS

Using Fetch() API facilitates asynchronous data fetching, enhancing user experience by ensuring that interactions are not blocked during data retrieval.

### Fetch API using Async/Await (WithoutAPI Key)

```javascript
// DOM elements initialization
const userInput = document.getElementById('userInput');
const dataContainer = document.getElementById('dataContainer');
const errorMessage = document.getElementById('errorMessage');
const searchButton = document.getElementById('searchButton');

// Function to fetch data from API asynchronously
async function fetchData() {
  try {
    // Encode user input for URL parameter
    const encodedInput = encodeURIComponent(userInput.value);

    // Fetch request to a public API without API key requirement
    const response = await fetch(
      `https://api.example.com/data?search=${encodedInput}`
    );

    // Check response status
    if (!response.ok) {
      // Throw error for unsuccessful response
      throw new Error(`HTTP error! Status: ${response.status}`);
    }

    // Parse response to JSON
    const data = await response.json();

    // Display the entered user input
    userInput.textContent = `User Input: ${userInput.value}`;

    // Extract values from response
    const value1 = data.property1; // Use actual data property names
    const value2 = data.property2; // Use actual data property names

    // Update DOM with response data
    dataContainer.textContent = `Value 1: ${value1}, Value 2: ${value2}`;
  } catch (error) {
    // Handle and display error
    errorMessage.textContent = `Error: ${error.message}`;
  }
}
// Attach an event listener to the search button
searchButton.addEventListener('click', fetchData);
```

### Fetch API using Async/Await (With API Key)

```javascript
// DOM element references
const userInput = document.getElementById('userInput');
const dataContainer = document.getElementById('dataContainer');
const errorMessage = document.getElementById('errorMessage');
const searchButton = document.getElementById('searchButton');

// API key (note: secure it properly in real-world apps)
const apiKey = 'YOUR_API_KEY_HERE';

// Async function to fetch data from API
async function fetchData() {
  try {
    // Encode user input for URL inclusion
    const encodedInput = encodeURIComponent(userInput.value);

    // Fetch data from API with encoded input
    const response = await fetch(
      `https://api.example.com/data?api_key=${apiKey}&search=${encodedInput}`
    );

    // Check for successful response
    if (!response.ok) {
      throw new Error(`HTTP error! Status: ${response.status}`);
    }

    // Parse JSON response
    const data = await response.json();

    // Display user input
    userInput.textContent = `User Input: ${userInput.value}`;

    // Extract and display values from response
    const value1 = data.property1; // Adjust property names
    const value2 = data.property2; // Adjust property names

    dataContainer.textContent = `Value 1: ${value1}, Value 2: ${value2}`;
  } catch (error) {
    // Handle and display errors
    errorMessage.textContent = `Error: ${error.message}`;
  }
}

// Attach an event listener to the search button
searchButton.addEventListener('click', fetchData);
```

## [🔝 Back to Top](#top)

## 7.4 HANDLING JSON DATA

Working with JSON (JavaScript Object Notation) data in JavaScript.

### Parsing JSON Data

```javascript
const jsonString = '{"name": "John", "age": 30, "city": "New York"}';

try {
  const jsonData = JSON.parse(jsonString);
  const result = jsonData; // Use 'result' for further processing
} catch (error) {
  console.error('JSON Parsing Error:', error);
}
```

### Converting JavaScript Objects to JSON

```javascript
const person = {
  name: 'Alice',
  age: 25,
  city: 'San Francisco',
};

const jsonPerson = JSON.stringify(person);
const result = jsonPerson; // Use 'result' for further processing
```

### JSON Data Manipulation

```javascript
const data = {
  users: [
    { id: 1, name: 'John' },
    { id: 2, name: 'Alice' },
    { id: 3, name: 'Bob' },
  ],
};

// Accessing JSON Data
const userName = data.users[0].name;
const result1 = userName; // Use 'result1' for further processing

// Modifying JSON Data
data.users.push({ id: 4, name: 'Eve' });

// Converting Back to JSON
const updatedJsonData = JSON.stringify(data);
const result2 = updatedJsonData; // Use 'result2' for further processing
```

## [🔝 Back to Top](#top)

## 8.1 OBJECT-ORIENTED PROGRAMMING (OOP) IN JAVASCRIPT

Overview of Object-Oriented Programming (OOP) concepts in JavaScript.

### Object-Oriented Programming (OOP)

OOP is a programming paradigm that uses objects and classes to organize code.
In JavaScript, objects are at the core of OOP.

### Objects

Objects are instances of classes or constructors and encapsulate data and behavior.
They consist of properties (data) and methods (functions).

```javascript
// Creating an Object
const person = {
  name: 'John',
  age: 30,
  sayHello: function () {
    console.log(
      `Hello, my name is ${this.name} and I'm ${this.age} years old.`
    );
  },
};

// Accessing Object Properties
console.log(person.name); // Output: "John"

// Calling Object Methods
person.sayHello(); // Output: "Hello, my name is John and I'm 30 years old."
```

### Classes

Classes are blueprints or templates for creating objects.
They define the structure and behavior of objects.

```javascript
// Creating a Class
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  sayHello() {
    console.log(
      `Hello, my name is ${this.name} and I'm ${this.age} years old.`
    );
  }
}

// Creating Objects from a Class
const person1 = new Person('Alice', 25);
const person2 = new Person('Bob', 35);

// Calling Class Methods
person1.sayHello(); // Output: "Hello, my name is Alice and I'm 25 years old."
person2.sayHello(); // Output: "Hello, my name is Bob and I'm 35 years old."
```

### Constructor Method

The constructor method is called when an object is created from the class.
It initializes object properties.

### Class Inheritance

Classes can inherit properties and methods from another class using the'extends' keyword.
This promotes code reusability and the creation of class hierarchies.

```javascript
// Inheritance Example
class Animal {
  constructor(name) {
    this.name = name;
  }

  speak() {
    console.log(`${this.name} makes a sound.`);
  }
}

class Dog extends Animal {
  constructor(name, breed) {
    super(name); // Calls the parent class constructor
    this.breed = breed;
  }

  speak() {
    console.log(`${this.name} (a ${this.breed} dog) barks.`);
  }
}

const dog1 = new Dog('Buddy', 'Golden Retriever');
```

### Polymorphism

Polymorphism allows objects of different classes to be treated as objects ofa common superclass.
It enables flexibility and dynamic behavior based on the specific object type.

### Polymorphism Example

```javascript
const animals = [new Dog('Buddy', 'Golden Retriever'), new Animal('Kitty')];

for (const animal of animals) {
  animal.speak();
}
```

### Output

- "Buddy (a Golden Retriever dog) barks."
- "Kitty makes a sound."

### Object Composition

In JavaScript, you can create objects by composing or combining multiple objects,
allowing for more flexible and modular code.

```javascript
const address = {
  street: '123 Main St',
  city: 'Exampleville',
  zipCode: '12345',
};

const person = {
  name: 'John Doe',
  age: 30,
  address: address, // Object composition
};
```

## [🔝 Back to Top](#top)

## 9.1 Using HTML Elements in JavaScript

JavaScript enhances web pages by interacting with HTML elements to create dynamic content and user interfaces. Understanding the role of different HTML elements and their use cases in JavaScript is crucial for effective web development. This section provides a concise overview of common HTML elements used in JavaScript and their intended applications.

### `<div>`

- **Description:** Serves as a generic container for flow content, typically used to group elements for styling purposes or to control layout using CSS.
- **Use Case:** Use when you need a container for dynamic content manipulation or as a layout tool.

### `<span>`

- **Description:** An inline container used to mark up a part of a text, or a part of a document.
- **Use Case:** Ideal for styling small portions of text or for applying JavaScript actions to inline elements without disrupting document flow.

### `<button>`

- **Description:** Represents a clickable button.
- **Use Case:** Use for triggering actions or events, like submitting forms or interactive content changes.

### `<input>`

- **Description:** Allows the user to enter data. Various types include text, radio, checkbox, etc.
- **Use Case:** Use for creating interactive controls for forms to gather user input.

### `<form>`

- **Description:** Represents a document section containing interactive controls for submitting information.
- **Use Case:** Use when you need to collect user input or submissions.

### `<label>`

- **Description:** Represents a caption for an item in a user interface.
- **Use Case:** Use to associate text with form elements, improving accessibility and user interaction.

### `<select>`

- **Description:** Allows the selection from a list of options.
- **Use Case:** Use when you need to provide a dropdown menu of choices to the user.

### `<option>`

- **Description:** Defines an option in a select list.
- **Use Case:** Use to provide individual choices inside a `<select>` element.

### `<textarea>`

- **Description:** Allows multi-line text input.
- **Use Case:** Use when you need to allow users to enter larger amounts of text, such as comments or feedback.

### `<a>`

- **Description:** Defines a hyperlink, which can be used to link from one page to another.
- **Use Case:** Use for navigation purposes or linking to external documents, often with JavaScript to enhance functionality without changing pages.

### `<ul>`, `<ol>`, `<li>`

- **Description:** Represent unordered (`<ul>`), ordered (`<ol>`) lists, and list items (`<li>`), respectively.
- **Use Case:** Use for displaying a list of items dynamically. JavaScript can dynamically add, remove, or reorder list items.

## [🔝 Back to Top](#top)

## 9.2 Choosing Between Objects and Arrays

In JavaScript, both objects and arrays are used to store collections of data. However, choosing the right type of data structure for your data can significantly impact the readability, efficiency, and simplicity of your code. This section aims to provide guidance on when to use objects and when to use arrays.

### Understanding Objects

Objects are key-value pairs where each key is a string and the value can be anything. They are ideal for storing data with named properties.

#### When to Use Objects

- **Descriptive Data:** Use objects when you need to store data with descriptive properties. For example, user profiles, where each property (name, age, email) describes the user.
- **Unique Keys:** Use objects when each entry has a unique key, and you might need to look up data based on those keys.
- **Variable Properties:** Use objects when the properties of your data might vary from one item to another.

**Example:**

```javascript
const userProfile = {
  name: 'John Doe',
  age: 30,
  email: 'johndoe@example.com',
};
```

### Understanding Arrays

Arrays are ordered collections of values. They are best suited for storing lists of items where order matters.

#### When to Use Arrays

- **Ordered Data:** Use arrays when the order of your data is important. For example, a list of tasks in a to-do list application.
- **Homogeneous Elements:** Use arrays when you're dealing with a collection of similar items, where each item doesn't need a named key.
- **Simple List of Values:** Use arrays for simple lists where you primarily need to iterate over values or access them by index.

**Example:**

```javascript
const taskList = ['Buy groceries', 'Call Alice', 'Read a book'];
```

### Making the Choice

- **Complexity and Structure:** Use objects when your data is structured with multiple properties. Arrays are simpler and best for lists of items.
- **Access Pattern:** Use objects for direct access via keys and arrays for sequential access.
- **Performance Considerations:** Accessing elements by index in an array is generally faster than accessing values of an object by keys.

Choosing between objects and arrays depends on the nature of the data you're dealing with and how you plan to use it. Understanding these differences allows you to write more efficient, readable, and maintainable JavaScript code.

## [🔝 Back to Top](#top)

## 9.3 Managing User Input

Handling user input effectively is crucial for creating interactive and user-friendly web applications. JavaScript provides several methods and practices to manage user input efficiently, ensuring data integrity and enhancing user experience. This section covers useful tips and techniques for managing user input in fundamental JavaScript, focusing on aspects other than form validation.

### Trimming Input

- **Purpose:** Removes whitespace from both ends of a string.
- **Usage:** `input.trim()`
- **Scenario:** Always trim user input to avoid issues with unwanted spaces, especially in form fields like usernames and email addresses.

**Example:**

```javascript
const userInput = document.getElementById('username').value.trim();
```

### Converting Case for Case-Insensitive Comparison

- **Purpose:** Standardizes user input for comparison.
- **Usage:** `input.toLowerCase()` or `input.toUpperCase()`
- **Scenario:** Convert user input to lower or upper case to make comparisons case-insensitive, useful in login forms, search queries, etc.

**Example:**

```javascript
const emailInput = document.getElementById('email').value.toLowerCase();
```

### Handling Numeric Inputs

- **Purpose:** Ensures input is a number and meets certain conditions.
- **Usage:** `parseInt(input, 10)`, `parseFloat(input)`, or `Number(input)`
- **Scenario:** Use when you need to work with numbers, like quantities or prices. Always specify the radix with `parseInt` to avoid unexpected results.

**Example:**

```javascript
const quantity = parseInt(document.getElementById('quantity').value, 10);
```

### Validating Numeric Input with `isNaN()`

- **Purpose:** `isNaN(value)` checks if a value is NaN (Not-a-Number). It's useful for validating that the conversion from a string to a number was successful.
- **How it works:** After converting a string to a number, `isNaN()` can be used to check if the result is numeric. If `isNaN()` returns `true`, the input was not a valid number.
- **Example:**

  ```javascript
  const inputElement = document.getElementById('input').value;
  const number = Number(inputElement);

  if (isNaN(number)) {
    console.error('Input is not a valid number.');
  } else {
    console.log('Valid number input:', number);
  }
  ```

- **Use case:** Essential for form validation, ensuring that inputs expected to be numeric do not contain letters or other invalid characters.

### Sanitizing Input

- **Purpose:** Removes or escapes potentially harmful characters.
- **Usage:** Custom sanitization or using libraries.
- **Scenario:** Essential for preventing XSS (Cross-Site Scripting) attacks. Sanitize input if it will be inserted into the DOM or used in database queries.

**Example:**

```javascript
const sanitizedInput = userInput.replace(/</g, '&lt;').replace(/>/g, '&gt;');
```

### Conclusion

Properly managing user input is key to securing and enhancing the user experience in web applications. By employing these techniques, developers can ensure that input is handled safely and efficiently, paving the way for more robust and user-friendly web applications.

## [🔝 Back to Top](#top)

## 9.4 Form Validation

Form validation is a critical aspect of web development, ensuring that the data submitted by users meets specific criteria before being processed. Effective validation improves data quality, enhances security, and provides a better user experience by preventing errors and guiding users through the input process.

### Client-Side Validation

Client-side validation occurs in the browser before the data is submitted to the server. It provides immediate feedback to users and reduces server load.

#### HTML5 Validation Attributes

- **Purpose:** Leverage browser capabilities to perform basic validations without additional code.
- **Usage:** Attributes like `required`, `type="email"`, `minlength`, `maxlength`, and `pattern`.
- **Scenario:** Use for simple validations such as required fields, email formats, and numerical constraints.

**Example:**

```html
<input
  type="email"
  id="email"
  required
  pattern="^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$"
/>
```

#### JavaScript Custom Validation

- **Purpose:** Implement complex or custom logic that cannot be achieved with HTML5 attributes alone.
- **Usage:** JavaScript to create custom validation functions triggered on form events.
- **Scenario:** Use for complex scenarios like password strength, input dependency checks, or asynchronous validations (e.g., checking username availability).

**Example:**

```javascript
document.getElementById('form').addEventListener('submit', function (event) {
  const email = document.getElementById('email').value;
  if (!email.match(/^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/)) {
    event.preventDefault();
    // Display an error message or highlight the input field
  }
});
```

### Providing Feedback

- **Purpose:** Communicate validation results to the user, highlighting errors or confirming correct inputs.
- **Usage:** Dynamically update the DOM to display error messages or visual cues.
- **Scenario:** Use immediately upon input (real-time feedback) or after submitting the form (summary feedback).

**Example:**

```javascript
if (!isValidEmail(email)) {
  document.getElementById('email-error').innerText =
    'Please enter a valid email address.';
  event.preventDefault();
}
```

Separating form validation into its own section emphasizes its importance in web development. By implementing both client-side validations with HTML5 and custom JavaScript, developers can ensure data integrity, enhance user interaction, and prevent unnecessary server processing for invalid data.

## [🔝 Back to Top](#top)

## 9.5 Leveraging Randomness with Math.random()

### Introduction

`Math.random()` is a powerful JavaScript function that generates a pseudo-random number between 0 (inclusive) and 1 (exclusive). This function is widely used in various programming scenarios, from simple tasks like randomizing UI elements to complex simulations and algorithms. Understanding how to effectively use `Math.random()` can add a dynamic and unpredictable element to your applications.

### Basic Usage

At its core, `Math.random()` provides the foundation for randomness in JavaScript. Here’s how you can start using it:

#### Generating a Random Number

```javascript
const randomNumber = Math.random();
console.log(randomNumber); // Any number between 0 and 1
```

#### Selecting a Random Item from an Array

Often, you need to pick an item randomly from a list. Here's how you can do it:

```javascript
const items = ['Apple', 'Banana', 'Cherry', 'Date'];
const randomIndex = Math.floor(Math.random() * items.length);
const randomItem = items[randomIndex];
console.log(randomItem); // Randomly selected item
```

### Advanced Applications

`Math.random()` can be adapted for more complex scenarios, enhancing its utility beyond simple random selection.

### Randomizing Within a Range

To generate a random number within a specific range, you can modify the output of `Math.random()`:

```javascript
function getRandomInRange(min, max) {
  return Math.random() * (max - min) + min;
}
console.log(getRandomInRange(1, 100)); // Random number between 1 and 100
```

### Weighted Random Selection

In situations where options have different probabilities of being chosen, a weighted random selection algorithm can be implemented:

```javascript
function weightedRandom(options) {
  let i,
    sum = 0,
    r = Math.random();
  for (i in options) {
    sum += options[i];
    if (r <= sum) return i;
  }
}
const choices = { A: 0.1, B: 0.3, C: 0.6 };
console.log(weightedRandom(choices)); // "C" has a higher chance of being selected
```

### Dynamic Randomness

`Math.random()` can be particularly useful in scenarios where the data is dynamic or the exact values are not known in advance. For example, in game development for spawning items at random locations or in simulations where random factors influence outcomes.

### Conclusion

`Math.random()` is a versatile function that, when combined with JavaScript’s other features, allows for a wide range of applications, from simple to complex. Whether you're making your UI elements more dynamic, selecting random items from a list, determining outcomes in games, or simulating real-world phenomena, understanding how to leverage randomness effectively can significantly enhance the functionality and experience of your applications.

## [🔝 Back to Top](#top)

## 9.6 Persisting Data with Web Storage

Web Storage allows web applications to store data locally within the user's browser, offering two main mechanisms: `localStorage` and `sessionStorage`. This section delves into practical applications of both, showcasing how they can be utilized in real-world web development scenarios.

### Introduction to Web Storage

- **localStorage:** Enables data storage across browser sessions. Data persists until explicitly cleared, making it suitable for storing user preferences or long-term data.
- **sessionStorage:** Limits data storage to the lifetime of the page session. It's cleared when the tab is closed, ideal for temporary data like form inputs or session-specific data.

### Practical Examples

#### Example 1: Saving User Preferences with localStorage

**Scenario:** A website allows users to choose a theme. Using localStorage, the selected theme persists across sessions, providing a consistent user experience.

```javascript
// Saving the selected theme
function saveTheme(theme) {
  localStorage.setItem('theme', theme);
}

// Applying the saved theme on page load
function applySavedTheme() {
  const theme = localStorage.getItem('theme');
  if (theme) {
    document.body.classList.add(theme);
  }
}

applySavedTheme();
```

#### Example 2: Storing Session Data with sessionStorage

**Scenario:** A multi-step form where user progress should not be lost if the page reloads, but doesn't need to persist beyond the current session.

```javascript
// Saving form data to sessionStorage
function saveFormData(step, data) {
  sessionStorage.setItem(`formStep${step}`, JSON.stringify(data));
}

// Retrieving form data on page load to restore state
function retrieveFormData(step) {
  const data = sessionStorage.getItem(`formStep${step}`);
  return data ? JSON.parse(data) : null;
}
```

#### Example 3: ShoppingCart Persistence

**Scenario:** An e-commerce site uses localStorage to persist the shopping cart contents even after the browser is closed, improving user experience by allowing users to return to their cart at a later time.

```javascript
// Adding item to cart and saving to localStorage
function addToCart(item) {
  let cart = JSON.parse(localStorage.getItem('shoppingCart')) || [];
  cart.push(item);
  localStorage.setItem('shoppingCart', JSON.stringify(cart));
}

// Loading the cart contents on page load
function loadCart() {
  const cart = JSON.parse(localStorage.getItem('shoppingCart')) || [];
  // Code to render cart items goes here
}
```

Web Storage, encompassing both localStorage and sessionStorage, offers robust solutions for persisting data in web applications. By leveraging these technologies, developers can enhance the user experience, providing seamless session continuity and personalized settings across visits. Through practical applications like theme selection, form data preservation, and shopping cart management, Web Storage proves to be an invaluable asset in modern web development.

## [🔝 Back to Top](#top)

## 9.7 Coding Logic vs Data Retrieval & Execution

Understanding the distinction between coding logic and data retrieval & execution in JavaScript is crucial for effective programming.

### Coding Logic

Involves the core computational aspects such as algorithms, conditional statements, loops, and functions. It's about the internal logic that doesn't directly interact with the outside world (user interface, external APIs).

- **Mathematical calculations:** Performing operations like addition, subtraction, multiplication, and division.
- **String manipulation:** Operations like concatenation, slicing, or pattern matching.
- **Conditional checks:** Making decisions based on certain conditions using if-else statements or switch cases.

### Data Retrieval and Execution

Focuses on interacting with external data sources (APIs, databases) and the user interface. It involves fetching, displaying, and reacting to data.
Includes fetching API data, handling user inputs, updating the web page dynamically.

- **Key Methods:** fetch(), .addEventListener(), .innerHTML, console.log, alert.

### return

Utilized within functions to output a value back to the caller. It serves as an internal mechanism for passing data between functions or parts of your code. The return statement does not produce any visible output in the user interface or console. It is purely for internal data flow within the application.

```javascript
function functionName(parameters) {
  // Function body
  // Compute value or perform operations

  return value; // Value to be returned
}
```

### When to use various methods of data execution

- **console.log:** Outputs debugging information to the browser's console, external to application logic and UI.
- **prompt:** Displays dialogue box that prompts the user for text input.
- **alert:** Displays a message to the user via a dialog box, directly interacting with the user, external to code logic.
- **.innerHTML/.innerText:** Changes an element's HTML/Text content, directly modifying the web page's visible content.

## [🔝 Back to Top](#top)

## 10.1 TIPS AND BEST PRACTICES

Tips for cleaner, more efficient and maintainable JavaScript code.

### 1. Use Descriptive Variable and Function Names

- Choose meaningful and descriptive names for variables and functions to improve code readability.
- Avoid overly abbreviated or cryptic names.

### 2. Consistent Code Formatting

- Follow a consistent code formatting style to enhance code maintainability.
- Consider using popular coding conventions like the Airbnb JavaScript Style Guide.

### 3. Comment Your Code

- Add comments to explain complex logic, important decisions, or the purpose of functions and variables.
- Use comments to provide context to your code for yourself and others.

### 4. Avoid Global Variables

- Minimize the use of global variables to prevent potential conflicts and improve code modularity.
- Use local variables or encapsulate code within functions or modules.

### 5. Embrace ES6 Features

- Familiarize yourself with ES6 (ECMAScript 2015) features and syntax enhancements.
- Utilize features like arrow functions, template literals, and destructuring for cleaner code.

### 6. Error Handling

- Implement proper error handling mechanisms, including try...catch blocks, to handle exceptions gracefully.

### 7. Optimize Loops

- Be mindful of loop performance when dealing with large data sets.
- Use efficient loop constructs and consider optimizations like loop unrolling.

### 8. Strict Mode

- Strict mode is a feature in JavaScript that introduces stricter rules for writing JavaScript code.
- It helps to prevent common coding errors and makes it easier to write secure JavaScript.
- To enable strict mode, add the text `'use strict';` at the beginning of a script or a function body

### 9. Modular Code

- Break down your code into reusable and modular components or functions.
- Embrace the concept of modules and imports for better code organization.

### 10. Testing

- Write unit tests to ensure the correctness of your code.
- Explore testing frameworks like Jest, Mocha, or Jasmine.

### 11. Stay Updated

- Keep up with the latest developments in JavaScript and web technologies.
- Follow industry best practices and consider performance optimizations.

### Further Learning Resources

- [MDN Web Docs (Mozilla Developer Network)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [JavaScript.info](https://javascript.info/)
- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

[🔝 Back to Top](#top)
