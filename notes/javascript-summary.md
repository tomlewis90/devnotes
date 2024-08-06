# JAVASCRIPT

## 1. JavaScript
- A high-level, interpreted programming language
- Primarily used for client-side web development
- Can also be used server-side (Node.js)

## 2. Variables and Data Types
- Declare variables with `let`, `const`, or `var`
- Basic data types: 
  - Number: `let age = 25;`
  - String: `let name = "John";`
  - Boolean: `let isStudent = true;`
  - Undefined: `let score;`
  - Null: `let empty = null;`
- Complex data types:
  - Object: `let person = {name: "John", age: 25};`
  - Array: `let colors = ["red", "green", "blue"];`

## 3. Operators
- Arithmetic: `+`, `-`, `*`, `/`, `%`, `**`
- Assignment: `=`, `+=`, `-=`, `*=`, `/=`
- Comparison: `==`, `===`, `!=`, `!==`, `>`, `<`, `>=`, `<=`
- Logical: `&&` (and), `||` (or), `!` (not)

## 4. Control Structures
- If statements:
  ```javascript
  if (condition) {
    // code
  } else if (anotherCondition) {
    // code
  } else {
    // code
  }
  ```
- Switch statements:
  ```javascript
  switch(expression) {
    case x:
      // code
      break;
    case y:
      // code
      break;
    default:
      // code
  }
  ```
- Loops:
  - For loop: `for (let i = 0; i < 5; i++) { }`
  - While loop: `while (condition) { }`
  - Do-while loop: `do { } while (condition);`
  - For...of loop (arrays): `for (let item of array) { }`
  - For...in loop (objects): `for (let key in object) { }`

## 5. Functions
- Function declaration:
  ```javascript
  function greet(name) {
    return `Hello, ${name}!`;
  }
  ```
- Arrow functions:
  ```javascript
  const greet = (name) => `Hello, ${name}!`;
  ```
- Parameters and arguments
- Return statement

## 6. Arrays
- Creating arrays: `let fruits = ["apple", "banana", "orange"];`
- Accessing elements: `fruits[0]`
- Array methods: `push()`, `pop()`, `shift()`, `unshift()`, `slice()`, `splice()`
- Iterating: `forEach()`, `map()`, `filter()`, `reduce()`

## 7. Objects
- Creating objects: 
  ```javascript
  let person = {
    name: "John",
    age: 30,
    greet: function() {
      console.log("Hello!");
    }
  };
  ```
- Accessing properties: `person.name` or `person["name"]`
- Methods
- This keyword

## 8. String Methods
- Length: `str.length`
- Changing case: `toUpperCase()`, `toLowerCase()`
- Extracting parts: `slice()`, `substring()`, `substr()`
- Replacing: `replace()`
- Concatenating: `concat()` or use the `+` operator

## 9. Number Methods
- `toString()`, `toFixed()`, `toPrecision()`
- `parseInt()`, `parseFloat()`
- `isNaN()`, `isFinite()`

## 10. Math Object
- Constants: `Math.PI`, `Math.E`
- Methods: `Math.round()`, `Math.floor()`, `Math.ceil()`, `Math.random()`

## 11. Date Object
- Creating dates: `new Date()`
- Getting date components: `getFullYear()`, `getMonth()`, `getDate()`, `getDay()`
- Setting date components: `setFullYear()`, `setMonth()`, `setDate()`

## 12. Error Handling
- Try...catch statement:
  ```javascript
  try {
    // code that may throw an error
  } catch (error) {
    // handle the error
  } finally {
    // always executed
  }
  ```
- Throwing custom errors: `throw new Error("Custom error message");`

## 13. DOM Manipulation
- Selecting elements: `getElementById()`, `querySelector()`, `querySelectorAll()`
- Modifying elements: `innerHTML`, `textContent`, `setAttribute()`
- Creating and removing elements: `createElement()`, `appendChild()`, `removeChild()`
- Event handling: `addEventListener()`

## 14. Asynchronous JavaScript
- Callbacks
- Promises
- Async/Await

## 15. ES6+ Features
- Template literals: `` `Hello, ${name}!` ``
- Destructuring: `const { name, age } = person;`
- Spread operator: `const newArray = [...oldArray];`
- Default parameters: `function greet(name = "Guest") { }`
- Classes and inheritance

Remember to practice these concepts regularly and build small projects to reinforce your learning. JavaScript is a vast language with many more advanced topics to explore as you progress!