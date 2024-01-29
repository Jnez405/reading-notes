# Dynamic web pages with JavaScript

## **Variables in JavaScript:**
   In JavaScript, a variable is a named storage location that holds data or values. Variables are used to store and manage information in a program. They provide a way to refer to a piece of data by a symbolic name, making the code more readable and allowing for flexibility in manipulating values.


   Certainly! Let's break down the concepts of "scope," "hoisting," and "reassignment" in the context of JavaScript:

### Scope:
- **Definition:** Scope refers to the context in which a variable is defined and can be accessed. It determines where a variable is visible and can be used within your code.
- **Example:** A variable declared inside a function has a function-level scope, meaning it is only accessible within that function.

### Hoisting:
- **Definition:** Hoisting is a behavior in JavaScript where variable and function declarations are moved to the top of their containing scope during the compilation phase. This allows you to use variables or functions before they are declared in your code.
- **Example:** In the case of `var` declarations, the variable is hoisted to the top of its function or global scope, making it accessible even before its declaration.

### Reassignment:
- **Definition:** Reassignment refers to the ability to change the value of a variable after it has been initially assigned.
- **Example:** If you declare a variable and later give it a new value, you are reassigning that variable.

### Examples:

#### Scope Example:
```javascript
function example() {
    // Variable 'x' is only visible within this function (function-level scope)
    var x = 10;
    console.log(x);  // Accessible here
}

// console.log(x);  // Error: 'x' is not defined outside the function
```

#### Hoisting Example:
```javascript
console.log(y);  // undefined (due to hoisting)

var y = 20;

console.log(y);  // 20
```

In the above example, the `var y` declaration is hoisted to the top of its containing scope during the compilation phase, allowing you to use it before its actual declaration.

#### Reassignment Example:
```javascript
let z = 30;  // Declaration and assignment

z = 40;  // Reassignment

console.log(z);  // 40
```

In this example, the variable `z` is declared, assigned an initial value (30), and later reassigned a new value (40).

Understanding these concepts is crucial for writing effective and predictable JavaScript code. Each plays a role in how variables are declared, accessed, and modified in different parts of your program.

## **Declaring a Variable:**
   Declaring a variable in JavaScript involves using the `var`, `let`, or `const` keyword followed by the chosen variable name. Here are examples of variable declarations:

   ```javascript
   var age;     // using var (older way, with function scope)
   let name;    // using let (block-scoped, introduced in ECMAScript 6)
   const PI = 3.14;  // using const (block-scoped and constant)
   ```
   In JavaScript, there are three keywords used for variable declaration: `var`, `let`, and `const`. Each has different characteristics and scoping rules.

- ## **`var` Declaration**
   - **Scope:** Variables declared with `var` have function-level scope. This means they are visible throughout the entire function where they are declared.
   - **Hoisting:** Variables declared with `var` are hoisted to the top of their scope during the compilation phase. This means you can use a variable before it's declared.
   - **Reassignment:** Variables declared with `var` can be reassigned.
  
   ```javascript
   function example() {
       var x = 10;
       if (true) {
           var y = 20;
           console.log(x);  // 10
       }
       console.log(y);  // 20
   }
   ```

- ## **`let` Declaration:**
   - **Scope:** Variables declared with `let` have block-level scope. They are only visible within the block (enclosed by curly braces) where they are declared.
   - **Hoisting:** Variables declared with `let` are hoisted, but they are not initialized until the line of code with the declaration is executed.
   - **Reassignment:** Variables declared with `let` can be reassigned.

   ```javascript
   function example() {
       let x = 10;
       if (true) {
           let y = 20;
           console.log(x);  // 10
       }
       // console.log(y);  // Error: y is not defined (outside the block)
   }
   ```

- ## **`const` Declaration:**
   - **Scope:** Variables declared with `const` also have block-level scope.
   - **Hoisting:** Like `let`, variables declared with `const` are hoisted but not initialized until the line of code with the declaration is executed.
   - **Reassignment:** Variables declared with `const` are constants and cannot be reassigned after their initial value is assigned. However, for objects and arrays, the properties or elements can be modified.

   ```javascript
   function example() {
       const x = 10;
       if (true) {
           const y = 20;
           console.log(x);  // 10
       }
       // x = 15;  // Error: Assignment to constant variable
   }
   ```

Choosing between `var`, `let`, and `const` depends on the scope and mutability requirements of the variable in your code. `const` is typically used for values that shouldn't be reassigned, while `let` is used for variables that may be reassigned. `var` is less commonly used in modern JavaScript due to its function-scoping behavior.

   Declaring a variable informs the JavaScript interpreter that a certain name is associated with a storage location where data can be stored.

## **Assignment Operator (=):**
   The assignment operator (`=`) is used to assign a value to a variable. After declaring a variable, you can use the assignment operator to give it an initial value or update its value later in the program. Here are examples of variable assignment:

   ```javascript
   age = 25;       // assigning the value 25 to the variable age
   name = "John";  // assigning the string "John" to the variable name
   ```

   You can also combine declaration and assignment in a single line:

   ```javascript
   let count = 0;  // declaring and assigning the value 0 to the variable count
   ```

## **Information Received from the User:**
   Information received from the user is typically referred to as "user input" or "user data." In the context of JavaScript, you can use methods like `prompt()` or handle events to capture user input. For example:

   ```javascript
   let userInput = prompt("Enter your name:");  // using prompt to get user input
   ```

   Here, the `prompt()` function displays a dialog box with a message, and the user can input data. The entered data is then stored in the variable `userInput`.
