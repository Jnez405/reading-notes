# HTML Links, JS Functions, and Intro to CSS Layout

### Why This Topic Matters
Understanding HTML links, JavaScript functions, and CSS layout is crucial for web development. These concepts form the foundation of building interactive and well-structured web pages. Mastering these will enhance our ability to create dynamic and accessible websites.

### HTML Links

#### Creating Hyperlinks

1. **To create a basic link, we wrap text or other content inside what element?**
   - We wrap the text or content inside an `<a>` (anchor) element to create a hyperlink.

2. **The href attribute contains what information?**
   - The `href` attribute contains the URL of the page that the link goes to. It stands for "hypertext reference."

3. **What are some ways we can ensure links on our pages are accessible to all readers?**
   - Use descriptive text within the anchor element to describe the link's destination.
   - Ensure the link text is distinguishable from regular text, usually by underlining it and using a different color.
   - Use ARIA (Accessible Rich Internet Applications) labels when necessary to provide additional context to screen readers.

### CSS Layout

#### CSS Layout: Normal Flow and Positioning

1. **What is meant by “normal flow”?**
   - Normal flow refers to the default way that HTML elements are laid out on the web page. Block-level elements stack vertically from top to bottom, and inline elements arrange horizontally from left to right within a block-level container.

2. **What are a few differences between block-level and inline elements?**
   - Block-level elements take up the full width available and start on a new line (e.g., `<div>`, `<p>`, `<h1>`).
   - Inline elements only take up as much width as necessary and do not start on a new line (e.g., `<span>`, `<a>`, `<strong>`).

3. **___ positioning is the default for every HTML element.**
   - Static positioning is the default for every HTML element.

4. **Name a few advantages to using absolute positioning on an element.**
   - It allows precise placement of elements relative to their nearest positioned ancestor, which can be useful for creating complex layouts.
   - Elements with absolute positioning do not affect the layout of other elements, making it easier to layer items.

5. **What is a key difference between fixed positioning and absolute positioning?**
   - Fixed positioning positions an element relative to the browser window, so it stays in the same place even when the page is scrolled. Absolute positioning, on the other hand, positions an element relative to its nearest positioned ancestor and will move with page scrolling.

### Learn JS

#### Functions – Reusable Blocks of Code

1. **Describe the difference between a function declaration and a function invocation.**
   - A function declaration defines a function with a specific name and body, allowing it to be called later. For example:
     ```javascript
     function greet() {
         console.log('Hello!');
     }
     ```
   - A function invocation calls or executes the function so that its code runs. For example:
     ```javascript
     greet(); // Outputs: Hello!
     ```

2. **What is the difference between a parameter and an argument?**
   - A parameter is a variable in the function declaration that acts as a placeholder for the value that will be passed when the function is called.
   - An argument is the actual value that is passed to the function when it is invoked.


### Pair Programming

1. **Greater Efficiency**
Pair programming is often perceived as less efficient because it involves two people working on the same task. However, the reality is that pair programming can lead to higher-quality code and quicker problem-solving. By working together, two developers can catch mistakes early and brainstorm solutions more effectively than one person working alone. This collaborative approach means that less time is spent on debugging and troubleshooting later, which can actually make the process more efficient in the long run.

2. **Learning from Fellow Students**
Pair programming exposes developers to different problem-solving techniques and coding styles. When two programmers with varying levels of experience and expertise collaborate, they can share knowledge and teach each other new approaches. This peer learning environment accelerates skill development and helps both programmers solidify their understanding of different concepts by explaining them to one another.

### Things I Want to Know More About

- How can I create custom accessible links using ARIA roles?
- What are some advanced CSS layout techniques beyond normal flow and positioning?
- How can I optimize JavaScript functions for performance in large-scale applications?