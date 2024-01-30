<a name="top"></a>

# ![JavaScript Icon](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/JS-icon.png)  JavaScript Simplified: An Efficient Learning Guide

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
## Fundamental Programming Concepts
- [3.1 Functions](#31-functions)
- [3.2 Loops](#32-loops)
- [3.3 Conditional Statements](#33-conditional-statements)
- [3.4 Arrays](#34-arrays)
- [3.5 Objects](#35-objects)
- [3.6 Error Handling](#36-error-handling)
## Global JavaScript Objects
- [4.1 String](#41-string)
- [4.2 Number](#42-number)
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
## Tips and Best Practices
- [9.1 Tips and Best Practices](#91-tips-and-best-practices)

---

## 1.1 Overview of JavaScript
Explore the JavaScript language and its versatile capabilities, including:
  - Being a high-level, interpreted programming language.
  - Supporting dynamic typing for variables with varying data types.
  - Embracing multiple programming paradigms: event-driven, functional, and imperative.

### ![JavaScript Core Features](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/cog.png) Core Features
Discover how JavaScript enhances user interaction on web pages by manipulating HTML and CSS. Learn how it handles asynchronous operations to make web applications more responsive.

### ![JavaScript and ECMAScript](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/js.png)  JavaScript and ECMAScript
Understand JavaScript's adherence to ECMAScript (ES) standards, including significant updates introduced in ES6/ES2015, such as let/const, arrow functions, and classes.

### ![JavaScript Environments](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/stack.png)  Environments
Explore JavaScript's versatility in both client-side (browser) and server-side (Node.js) development. See how it empowers the creation of dynamic web page content and back-end applications.

### ![JavaScript Role in Web Development](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/webdev.png)  Role in Web Development
Understand JavaScript's integral role in web development, including its interactivity, DOM manipulation, and server-side capabilities.

### ![Integration with Web Technologies](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/tech.png)  Integration with Web Technologies
Learn how JavaScript collaborates with HTML and CSS to deliver complete web page functionality. Discover its use of AJAX for asynchronous web tasks.

### ![JavaScript Libraries and Frameworks](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/react.png)  Libraries and Frameworks
Explore libraries like React and frameworks like Angular, Vue.js, and Ember.js that simplify common tasks and provide robust tools for building complex applications.

[🔝 Back to Top](#top)
---

## 1.2 JavaScript Code Order
The order of your code is vital for logical flow, efficient loading, and readability.


### ![JavaScript Libraries and Frameworks](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/question.png)  Why It Matters

- **Logical Flow:** Ensures proper function sequencing.
- **Loading Efficiency:** Affects resource loading and page speed.
- **Readability:** Enhances code comprehension.
- **Maintainability:** Facilitates updates and bug fixes.
- **Collaboration:** Simplifies teamwork and code sharing.

### ![JavaScript Libraries and Frameworks](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/list.png)  Code Order Variability
Optimal code order varies based on project needs and best practices:

- **Library/Framework Integration:** Follow library/framework guidelines (e.g., React prioritizes state and rendering).
- **Event-Driven Applications:** In event-driven apps (e.g., games or chat), focus on event handling and async tasks.
- **Complex Form Validation:** For intricate form validation, focus on form handling and validation early.
- **Performance Optimization:** Adjust the order for performance optimization as per your app's requirements.
- **Team Workflow:** Adapt to your team's workflow and code organization preferences when collaborating.

### ![JavaScript Libraries and Frameworks](https://github.com/george-GPT/JavaScript-Quick-Reference/raw/main/images/list2.png)  General JavaScript Order
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

[🔝 Back to Top](#top)
---

## 2.1 VARIABLES AND DECLARATIONS
Understanding variable declaration and scope in JavaScript.

- **'var':** Function-scoped variable declaration (uncommon in modern JS)
  - `var oldVar = "I am old";` Avoid using 'var' when possible

- **'let':** Block-scoped variable declaration (can be reassigned)
  - `let newLet = "I am new";` Preferred for variables that can change

- **'const':** Block-scoped and constant variable declaration (cannot be reassigned)
  - `const constantVar = "I am constant";` Use for variables that should not change

[🔝 Back to Top](#top)
---

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

[🔝 Back to Top](#top)
---

## 3.1 FUNCTIONS
Detailed exploration of functions in JavaScript, including parameters and advanced concepts.

### Function Declarations 
Standard way to define a function with parameters.

```javascript
function greet(name) {
return `Hello, ${name}!`;
}
console.log(greet("Alice"));
```

Outputs "Hello, Alice!"

### Function Parameters 
Functions can take parameters as input.

```javascript
function add(a, b) {
  return a + b;
}
console.log(add(5, 3)); // Outputs 8
```

### Default Parameters (ES6)
Assign default values to parameters.

```javascript
function say(message = "Hi") {
  console.log(message);
}
`say();` // Outputs "Hi"
`say("Hello");`; // Outputs "Hello"
```

### Rest Parameters (ES6)
Handle an indefinite number of parameters.

```javascript
function sumAll(...numbers) {
return numbers.reduce((acc, num) => acc + num, 0);
}
console.log(sumAll(1, 2, 3));
```

Outputs 6

### Arrow Functions (ES6) 
Concise way to write functions:
  - (parameters) => expression

```javascript
const multiply = (x, y) => x \* y;
console.log(multiply(2, 3));
```

Outputs 6

### IIFE (Immediately Invoked Function Expression)
Function that runs as soon as it is defined.

```javascript
(function() {
console.log("This function runs right away!");
})();
```

### Higher-Order Functions
Functions that take or return other functions.

```javascript
function applyOperation(a, b, operation) {
  return operation(a, b);
}
`const result = applyOperation(4, 2, multiply);` // Using the multiply arrow function
`console.log(result);`; // Outputs 8
```

[🔝 Back to Top](#top)
---

## 3.2 LOOPS
Loops enable repetitive execution of code, streamlining tasks like array traversal and conditional iterations.

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
const person = { name: "Alice", age: 30 };
for (const key in person) {
  console.log(`${key}: ${person[key]}`); // Outputs: "name: Alice", "age: 30"
}
```

### dor...of Loop (ES6)
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

[🔝 Back to Top](#top)
---

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
Executes code based on the value of an expression.

```javascript
switch (expression) {
  case x:
    // Code for case x
    break;
  case y:
    // Code for case y
    break;
  default:
  // Default code if none of the above cases are true
}
```

[🔝 Back to Top](#top)
---

## 3.4 ARRAYS
Detailed guide on JavaScript Arrays, covering array manipulation methods, iteration, and array-specific operations.

### Properties
- `Array.length` Reflects the number of elements in an array.
- `Array.prototype` Represents the prototype for the Array constructor and allows to add new properties and methods to all Array objects.

### Methods
- `Array.from(arrayLike[, mapFn[, thisArg]])` Creates a new Array instance from an array-like or iterable object.
- `Array.isArray(obj)` Returns true if a variable is an array, if not false.
- `Array.of("element1", "element2");` Creates a new Array instance with a variable number of arguments, regardless of number or type of the arguments.

### Mutator Methods
- `arr.copyWithin(target, start, end)` Copies a sequence of array elements within the array.
- `arr.fill(value, start, end)` Fills all the elements of an array from a start index to an end index with a static value.
- `arr.pop()` Removes the last element from an array and returns that element.
- `arr.flat()` Merges nested array into one single array.
- `arr.push("element1", "element2");` Adds one or more elements to the end of an array and returns the new length of the array.
- `arr.reverse()` Reverses the order of the elements of an array in place — the first becomes the last, and the last becomes the first.
- `arr.shift()` Removes the first element from an array and returns that element.
- `arr.sort()` Sorts the elements of an array in place and returns the array.
- `array.splice(start, deleteCount, item1, item2)` Adds and/or removes elements from an array.
- `arr.unShift("element1", "element2");` Adds one or more elements to the front of an array and returns the new length of the array.

### Acessor Methods
- `arr.at(index)` Returns the element at the specified index in the array.
- `arr.concat(value1, value2, array2)` Returns a new array comprised of this array joined with other array(s) and/or value(s).
- `arr.includes(searchElement, fromIndex)` Determines whether an array contains a certain element, returning true or false as appropriate.
- `arr.indexOf(searchElement[, fromIndex])` Returns the first (least) index of an element within the array equal to the specified value, or -1 if none is found.
- `arr.join(separator)` Joins all elements of an array into a string.
- `arr.lastIndexOf(searchElement, fromIndex)` Returns the last (greatest) index of an element within the array equal to the specified value, or -1 if none is found.
- `arr.slice(begin, end)` Extracts a section of an array and returns a new array.
- `arr.toString()` Returns a string representing the array and its elements. 
  - Overrides the Object.prototype.toString() method.
- `arr.toLocaleString(locales, options)` Returns a localized string representing the array and its elements. 
  - Overrides the `Object.prototype.toLocaleString()` method.

### Iteration Methods
- `arr.every(callback[, thisArg])` Returns true if every element in this array satisfies the provided testing function.
- `arr.filter(callback[, thisArg])` Creates a new array with all of the elements of this array for which the provided filtering function returns true.
- `arr.find(callback[, thisArg])` Returns the found value in the array, if an element in the array satisfies the provided testing function or undefined if not found.
- `arr.findIndex(callback[, thisArg])` Returns the found index in the array, if an element in the array satisfies the provided testing function or -1 if not found.
- `arr.forEach(callback[, thisArg])` Calls a function for each element in the array.
- `arr.keys()` Returns a new Array Iterator that contains the keys for each index in the array.
- `arr.map(callback[, initialValue])` Creates a new array with the results of calling a provided function on every element in this array.
- `arr.reduce(callback[, initialValue])` Apply a function against an accumulator and each value of the array (from left-to-right) as to reduce it to a single value.
- `arr.reduceRight(callback[, initialValue])` Apply a function against an accumulator and each value of the array (from right-to-left) as to reduce it to a single value.
- `arr.some(callback[, initialValue])` Returns true if at least one element in this array satisfies the provided testing function.
- `arr.values()` Returns a new Array Iterator object that contains the values for each index in the array.

[🔝 Back to Top](#top)
---

## 3.5 OBJECTS
Overview of JavaScript Object, its properties, and methods.

### Creating an Object
- `const myObject = { key1: 'value1', key2: 'value2' };` Object literal with two properties

### Accessing Properties
- `console.log(myObject.key1);` 'value1'
- `console.log(myObject['key2']);` 'value2'

### Adding Properties
- `myObject.key3 = 'value3';` Adding a new property 'key3'

### Deleting Properties
- `delete myObject.key2;` Removing property 'key2'

### Methods of the Object Constructor
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
 
### Looping Through Properties Using for...in

```javascript
for (const key in myObject) {
  console.log(key, myObject[key]); // Logs key and value of each property
}
```

[🔝 Back to Top](#top)
---

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
    throw new Error("Input is not a number"); // Custom error
  }
}
```

### Example Usage of throw

```javascript
try {
  checkNumber("A");
} catch (e) {
  console.log(e.message); // Output: Input is not a number
}
```

[🔝 Back to Top](#top)
---

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

[🔝 Back to Top](#top)
---

## 4.2 NUMBERS
Fundamental number-related functionalities in JavaScript.

### parseInt(string, radix)
- `parseInt("10", 10);` Converts the string "10" to an integer (base 10).
- `parseInt("10", 2);` Converts the string "10" to an integer (base 2, binary).

### parseFloat(string)
`parseFloat("3.14");` Converts the string "3.14" to a floating-point number.

### toFixed(digits)

```javascript
const num = 123.456;
num.toFixed(2); // Returns "123.46" - formats the number using fixed-point notation.
```

### Array Destructuring

```javascript
const fruits = ["Apple", "Banana", "Cherry"];
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
- `Number.MIN_VALUE;`  The smallest positive representable number
- `Number.parseFloat("5.5");` 5.5
- `Number.parseInt("10", 10);` 10

[🔝 Back to Top](#top)
---

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

[🔝 Back to Top](#top)
---

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

[🔝 Back to Top](#top)
---

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
const element = document.getElementById("example-element");

// Modify the element's content
element.innerHTML = "This is the new content.";

// This updates the HTML content of the element.
```

[🔝 Back to Top](#top)
---

## 5.2 ACCESSING AND MODIFYING DOM ELEMENTS
Methods for selecting, creating, and modifying DOM elements.

### Accessing Elements
- `document.getElementById(id);` Gets an element by its ID.
- `document.getElementsByTagName(name);` Returns a live HTMLCollection of elements with the given tag name.
- `document.getElementsByClassName(className);` Returns a live HTMLCollection of elements with the given class name.
- `document.querySelector(selector);` Returns the first element matching the specified CSS selector.
- `document.querySelectorAll(selector);` Returns a NodeList of all elements matching the specified CSS selector.
 
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

[🔝 Back to Top](#top)
---

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
const list = document.getElementById("myList");

// Get the text content of the first child node
const firstChildText = list.firstChild.innerText;

// Change the HTML content of the list
list.innerHTML = "<li>New Item 1</li><li>New Item 2</li>";

// Create a new list item element
const newItem = document.createElement("li");
newItem.innerText = "New Item 3";

// Insert the new item at the beginning of the list
list.insertBefore(newItem, list.firstChild);

```

[🔝 Back to Top](#top)
---

## 5.4 DOM EVENT HANDLING
Methods for attaching, handling, and removing event listeners on DOM elements.

### Adding Event Listeners

### Anonymous Function Event Listener
For simple, one-time event handling without the need for additional checks or complex logic:
```javascript
document.getElementById("myButton").addEventListener("click", function() {
  handleButtonClick();
});
```

### Named Function Event Listener
For additional checks, complex logic, or reusability, using a named function offers better code organization and maintainability:
```javascript
document.getElementById("myButton").addEventListener("click", buttonClickFunction);
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
element.addEventListener("click", function(event) {
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
document.addEventListener("keydown", function(event) {
  if (event.key === "Enter") {
    // Call your function here
    // Example: handleEnterKey();
  }
});

```

[🔝 Back to Top](#top)
---

## 6.1 ASYNCHRONOUS OPERATIONS IN JAVASCRIPT
This section covers JavaScript's asynchronous operations, including network requests and user interactions.

### What Are Asynchronous Operations?
Asynchronous operations are tasks that occur independently of the main program flow. They often involve actions like fetching data from a remote server, reading files, or waiting for user interactions. These tasks can take time to complete, and they may not block the execution of other parts of your program.

### Common Approaches
There are several approaches for handling asynchronous operations in JavaScript:

- **Callbacks (Traditional Approach):** Callbacks are a common way to manage asynchronous tasks. They involve passing a function as an argument to another function to execute when the asynchronous operation is complete.

- **Promises (Structured Approach):** Promises provide a more structured way to handle asynchronous operations. They represent a value that may be available now or in the future, allowing you to perform actions once the operation completes.

- **Async/Await (Modern Approach):** Async/await is a set of JavaScript keywords that simplifies working with promises. It allows you to write asynchronous code that resembles synchronous code, improving code readability and maintainability.

[🔝 Back to Top](#top)
---

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

[🔝 Back to Top](#top)
---

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

[🔝 Back to Top](#top)
---

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

[🔝 Back to Top](#top)
---
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

[🔝 Back to Top](#top)
---

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

[🔝 Back to Top](#top)
---

## 7.3 MAKING API REQUESTS
Using Fetch() API facilitates asynchronous data fetching, enhancing user experience by ensuring that interactions are not blocked during data retrieval. 

### Fetch API using Async/Await (WithoutAPI Key)

```javascript
// DOM elements initialization
const userInput = document.getElementById("userInput");
const dataContainer = document.getElementById('dataContainer');
const errorMessage = document.getElementById('errorMessage');
const searchButton = document.getElementById('searchButton');

// Function to fetch data from API asynchronously
async function fetchData() {
  try {
    // Encode user input for URL parameter
    const encodedInput = encodeURIComponent(userInput.value);

    // Fetch request to a public API without API key requirement
    const response = await fetch(`https://api.example.com/data?search=${encodedInput}`);
    
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
const userInput = document.getElementById("userInput");
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
    const response = await fetch(`https://api.example.com/data?api_key=${apiKey}&search=${encodedInput}`);
    
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

[🔝 Back to Top](#top)
---

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
  city: 'San Francisco'
};

const jsonPerson = JSON.stringify(person);
const result = jsonPerson; // Use 'result' for further processing
```

### JSON Data Manipulation

```javascript
const data = {
  users: [
    { id: 1, name: "John" },
    { id: 2, name: "Alice" },
    { id: 3, name: "Bob" },
  ],
};

// Accessing JSON Data
const userName = data.users[0].name;
const result1 = userName; // Use 'result1' for further processing

// Modifying JSON Data
data.users.push({ id: 4, name: "Eve" });

// Converting Back to JSON
const updatedJsonData = JSON.stringify(data);
const result2 = updatedJsonData; // Use 'result2' for further processing
```

[🔝 Back to Top](#top)
---

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
  name: "John",
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
const person1 = new Person("Alice", 25);
const person2 = new Person("Bob", 35);

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

const dog1 = new Dog("Buddy", "Golden Retriever");
```

### Polymorphism 
Polymorphism allows objects of different classes to be treated as objects ofa common superclass. 
It enables flexibility and dynamic behavior based on the specific object type.

### Polymorphism Example

```javascript
const animals = [new Dog("Buddy", "Golden Retriever"), new Animal("Kitty")];

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
  street: "123 Main St",
  city: "Exampleville",
  zipCode: "12345",
};

const person = {
  name: "John Doe",
  age: 30,
  address: address, // Object composition
};
```

[🔝 Back to Top](#top)
---

## 9.1 TIPS AND BEST PRACTICES
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

### 8. Modular Code
- Break down your code into reusable and modular components or functions.
- Embrace the concept of modules and imports for better code organization.

### 9. Testing
- Write unit tests to ensure the correctness of your code.
- Explore testing frameworks like Jest, Mocha, or Jasmine.

### 10. Stay Updated
- Keep up with the latest developments in JavaScript and web technologies.
- Follow industry best practices and consider performance optimizations.



### Further Learning Resources

- [MDN Web Docs (Mozilla Developer Network)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [JavaScript.info](https://javascript.info/)
- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

[🔝 Back to Top](#top)