# Programming with JavaScript

## **Control Flow:**
  - Order of statement execution.
  - Uses structures like `if`, `for`, `while` to control flow.

Certainly! Here are notes for `if`, `for`, and `while` statements in JavaScript:

- **if Statement:**
  - Used for conditional execution.
  - Syntax:
    ```javascript
    if (condition) {
        // code to be executed if the condition is true
    }
    ```
  - Example:
    ```javascript
    let x = 10;
    if (x > 5) {
        console.log("x is greater than 5");
    }
    ```

- **for Loop:**
  - Used for iterating over a block of code a specific number of times.
  - Syntax:
    ```javascript
    for (initialization; condition; update) {
        // code to be executed in each iteration
    }
    ```
  - Example:
    ```javascript
    for (let i = 0; i < 5; i++) {
        console.log(i);
    }
    ```
  
- **while Loop:**
  - Used for iterating as long as a specified condition is true.
  - Syntax:
    ```javascript
    while (condition) {
        // code to be executed while the condition is true
    }
    ```
  - Example:
    ```javascript
    let count = 0;
    while (count < 3) {
        console.log(count);
        count++;
    }
    ```

Remember:
- `if` statements are for conditional execution.
- `for` loops are for iterating a specific number of times.
- `while` loops are for iterating as long as a condition is true.

Practice using these structures to control the flow of your JavaScript code.

## **JavaScript Function:**
  - Reusable block of code.
  - Defined with `function` keyword, name, parameters, and code block.

    ```javascript
    function greet(name) {
        console.log("Hello, " + name + "!");
    }
    ```

## **Invoking/Calling a Function:**
  - Execute the code inside a function.
  - Use function name followed by parentheses.

    ```javascript
    greet("John");  // Invokes greet function with "John" as an argument
    ```

## **Parentheses in Function Definition:**
  - Declare parameters a function accepts.
  - Used when calling the function with arguments.

    ```javascript
    function add(a, b) {
        return a + b;
    }
    ```

    ```javascript
    let result = add(3, 5);  // Invokes add function with arguments 3 and 5
    ```

    ```javascript
    function sayHello() {
        console.log("Hello!");
    }

    sayHello();  // Invokes sayHello function without arguments
    ```

In summary: control flow manages statement order, functions are reusable code blocks, invoking a function means executing it, and parentheses in function definitions declare parameters and are used when calling the function with arguments.
