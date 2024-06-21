# HTML Fundamentals Expanded and Semantic Elements Overview

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

   **
### Ways to Apply CSS to HTML:

1. **External Stylesheet**:
   - Create a separate `.css` file containing all CSS rules.
   - Link the CSS file to HTML using the `<link>` element within the `<head>` section.
   - Example:
     ```html
     <link rel="stylesheet" type="text/css" href="styles.css">
     ```

2. **Internal Stylesheet**:
   - Define CSS rules directly within the HTML `<style>` element in the `<head>` section.
   - Example:
     ```html
     <style>
       /* CSS rules here */
     </style>
     ```

3. **Inline Styles**:
   - Apply CSS rules directly to individual HTML elements using the `style` attribute.
   - Example:
     ```html
     <h1 style="color: blue;">Heading</h1>
     ```

## Reasons to Avoid Using Inline Styles:

1. **Maintainability**:
   - Inline styles make it challenging to maintain consistency across the website since each style is applied individually to elements.

2. **Readability**:
   - Mixing HTML structure with styling attributes can clutter the code and reduce readability, especially in large projects.

3. **Specificity Issues**:
   - Inline styles have the highest specificity, making it difficult to override them with external or internal stylesheets.

4. **Accessibility**:
   - Inline styles can hinder accessibility features as they may not be properly interpreted by assistive technologies.

5. **Debugging**:
   - Troubleshooting becomes more complex when styles are scattered throughout the HTML document, as opposed to being centralized in a separate stylesheet.

6. **Caching and Performance**:
   - External stylesheets can be cached by the browser, resulting in faster loading times for subsequent page visits. Inline styles are loaded every time the HTML document is accessed, potentially impacting performance.
   **

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
---
```css
   h2 {
     color: black;
     padding: 5px;
   }
```

- **Selector**: `h2` represents the selector. It targets HTML `<h2>` elements to apply the defined styles.

- **CSS Declarations**: 
  - `color: black;`
  - `padding: 5px;`
  
  These are the CSS declarations. Each declaration consists of a property and a value, separated by a colon (`:`).

- **Properties**:
  - `color`
  - `padding`
  
  These are the components considered as properties. They define specific stylistic attributes that will be applied to the selected HTML elements.

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

## Things I Want to Know More About
can you have more than one css styles file?


