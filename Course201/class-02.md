## HTML Fundamentals Expanded and Semantic Elements Overview

1. **Importance of Semantic Elements in HTML:**
   - Semantic elements provide meaning and structure to content.
   - They enhance SEO, accessibility, code readability, developer guidance, and future-proofing.

2. **Levels of Headings in HTML:**
   - HTML offers six levels of headings, from `<h1>` to `<h6>`.
   - `<h1>` denotes the highest level, while `<h6>` represents the lowest.

3. **Uses of `<sup>` and `<sub>` Elements:**
   - `<sup>`: Defines superscript text.
   - `<sub>`: Defines subscript text.
   - Commonly used for mathematical equations, footnotes, chemical formulas, and annotations.

4. **Attributes for `<abbr>` Element:**
   - When using `<abbr>` to define abbreviations or acronyms:
   - Add the `title` attribute to provide the full expansion of the term.
   - Enhances user understanding when hovering over or focusing on the element.

## How CSS Is Structured

1. **Applying CSS to HTML:**
   - Three methods: External, internal, and inline styles.
   - **External stylesheet:** Linked using `<link>` element in HTML `<head>`.
   - **Internal stylesheet:** CSS placed within `<style>` tags in HTML `<head>`.
   - **Inline styles:** CSS directly applied to HTML elements using `style` attribute.

2. **Selectors:**
   - Target HTML elements for styling purposes.
   - Examples: Element selectors (`h1`, `p`), class selectors (`.classname`), ID selectors (`#idname`).

3. **Specificity:**
   - Determines which style rule takes precedence.
   - Priority: Inline styles > IDs > Classes > Elements.

4. **Properties and Values:**
   - **Properties:** Define specific stylistic attributes (e.g., `color`, `font-size`).
   - **Values:** Assign styling to properties (e.g., `blue`, `12px`).

5. **Functions:**
   - Provide functionality within CSS.
   - Example: `calc()` function for mathematical operations.

6. **@Rules:**
   - Provide instructions or conditional logic for CSS.
   - Example: `@import`, `@media` for media queries.

7. **Shorthands:**
   - Combine multiple property-value pairs into a single line.
   - Examples: `font`, `background`, `padding`.

8. **Comments:**
   - Enhance code readability and understanding.
   - Enclosed in `/* */`.

9. **White Space:**
   - Ignored by browsers but improves code readability.
   - Separate property names and values with spaces.

## Here's an example of well-structured CSS code:


```css
/* Resetting default margin and padding */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Body styling */
body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  color: #333;
}

/* Header styling */
header {
  background-color: #007bff;
  color: #fff;
  padding: 10px 20px;
}

/* Navigation menu */
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav ul {
  list-style: none;
  display: flex;
}

nav ul li {
  margin-right: 20px;
}

nav ul li:last-child {
  margin-right: 0;
}

nav ul li a {
  text-decoration: none;
  color: #fff;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: #ffd700; /* Change color on hover */
}

/* Main content area */
.main-content {
  padding: 20px;
}

/* Footer styling */
footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px 0;
}
```


## Learn JS

1. **String Data Type:**
   - Enclosed in single quote marks ('').
   - Represents a sequence of characters.
   - Example: 'Hello, World!'

2. **JavaScript Operators:**
   - **Arithmetic Operators:**
     - Perform mathematical calculations.
     - Examples: +, -, *, /, %
   - **Assignment Operators:**
     - Assign values to variables.
     - Examples: =, +=, -=, *=, /=

3. **Real-World Problem Solved with a Function:**
   - **Problem:**
     - Calculate the total cost of a shopping cart with discounts applied.
   - **Solution:**
     - Create a JavaScript function named calculateTotalCost.
     - Parameters: item prices, quantities, discount rates.
     - Logic: Calculate subtotal, apply discounts based on conditions.
     - Return: Final total cost.
   - **Benefits:**
     - Encapsulates logic for reusability.
     - Ensures consistency and maintainability in code.

## Making Decisions In Your Code – Conditionals

1. **If Statement in JavaScript:**
   - Checks a condition.
   - If the condition evaluates to true, the associated code block will execute.

2. **Purpose of Else If:**
   - Extends the if statement to check additional conditions if the initial condition evaluates to false.
   - Provides an alternative condition to execute if the preceding if statement condition is false.

3. **Types of Comparison Operators:**
   - **Equal to (==):** Checks if two values are equal.
   - **Not equal to (!=):** Checks if two values are not equal.
   - **Greater than (>):** Checks if one value is greater than another.

4. **Difference Between Logical Operators && and ||:**
   - **&& (Logical AND):**
     - Returns true if both operands are true.
     - If any operand is false, returns false.
   - **|| (Logical OR):**
     - Returns true if at least one operand is true.
     - If both operands are false, returns false.
