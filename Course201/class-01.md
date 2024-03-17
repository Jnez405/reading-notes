# Web Basics and JavaScript Fundamentals

HTTP, a digital courier in the web's vast domain,
Sends data through cyberspace like a silent, swift refrain.
From sender to receiver, it glides with elegant grace,
Connecting computers, in a digital embrace.


**Parsing HTML, CSS, and JS files in the browser:**
- **HTML Parsing:**
  - Browser reads HTML to build a structure for the webpage.
- **CSS Parsing:**
  - It understands the webpage's style rules.
- **JS Parsing:**
  - Stops reading HTML/CSS to run JavaScript, which can change the webpage.

**Finding images to add to a Website:**
- **Online Repositories:**
  - Websites like Unsplash offer free images.
- **Design Tools:**
  - Programs like Photoshop help make images.
- **Photography:**
  - You can take your own photos.
- **Open-source Projects:**
  - Some projects offer images you can use.

**Creating a String vs a Number in JavaScript:**
- **String:**
  - Text with single or double quotes around it.
- **Number:**
  - Just write the number, no quotes needed.

**Variable and its Importance in JavaScript:**
- **Variable:**
  - It's like a box you can put things in, with a name.
  - You say what's inside using `var`, `let`, or `const`.
- **Importance:**
  - Helps store and change data in programs.
  - Makes code easier to understand.
  - Useful for reusing data and making programs work better.

# Introduction to HTML

**HTML Attribute:**
   - Provides extra information about an element.
   - Found within the start tag of an HTML element.
   - Modifies or enhances the element's behavior or appearance.

**Anatomy of an HTML Element:**
   - **Start Tag:** Marks the beginning of the element.
   - **Attributes:** Optional extra information within the start tag.
   - **Content:** The actual data or content within the element.
   - **End Tag:** Marks the end of the element (if required).
   - **Nested Elements:** Elements contained within other elements.

**Difference between `<article>` and `<section>` Tags:**
   - `<article>`: Self-contained content, like a standalone article or post.
   - `<section>`: Groups related content thematically within a document.

**Elements in a "Typical" Website:**
   - `<header>`: Introductory content or navigation links.
   - `<nav>`: Navigation links.
   - `<main>`: Main content area.
   - `<article>`: Independent content.
   - `<section>`: Grouped content.
   - `<footer>`: Closing content, e.g., copyright info.

**Metadata and SEO:**
   - Provides information to search engines.
   - Influences indexing and ranking in search results.
   - Includes page descriptions, keywords, character encoding, etc.

**Using `<meta>` Tag for Metadata:**
   - Placed within the `<head>` section of HTML.
   - Attributes like `name` and `content` specify metadata type and value.
   - Examples: page descriptions, keywords, viewport settings.
---
# How to start to design a Website.
**What is the first step to designing a Website?**
- The first step to designing a website is to define its goals and purpose.
- This involves listing and prioritizing what you want to achieve with the website, considering both web-related and offline goals.
- By having a clear understanding of your objectives, you can effectively plan and execute the website design process.

**What is the most important question to answer when designing a Website?**
- The most important question to answer when designing a website is: "What exactly do I want to accomplish with this website?"
- Defining the goals and purpose of the website sets the direction for the entire design process.
- By understanding the objectives, you can determine how the website will help you reach those goals and what needs to be done to achieve them.

___
# Semantics

**Why should you use an `<h1>` element over a `<span>` element to display a top level heading?**
- The `<h1>` element is a semantic element specifically designed to represent a top-level heading in HTML.
- Using `<h1>` provides meaning and structure to the content, indicating to both browsers and assistive technologies that the text is a top-level heading.
- Semantic elements like `<h1>` convey the hierarchical structure of the document, making it easier for search engines to understand the importance and relevance of the content.
- In contrast, using a `<span>` element styled to look like a heading lacks semantic meaning and may lead to confusion for both humans and machines interpreting the content.

**What are the benefits of using semantic tags in our HTML?**
- Semantic tags provide meaning and context to the content, making it more understandable for both humans and machines.
- Benefits of using semantic tags include:
  1. **Improved SEO:** Search engines can better understand the content and relevance of the webpage, leading to improved search engine rankings.
  2. **Accessibility:** Screen readers and other assistive technologies rely on semantic HTML to interpret and present content to users with disabilities, enhancing accessibility.
  3. **Code Readability:** Semantic markup improves the readability and maintainability of code by clearly indicating the purpose and structure of the content.
  4. **Developer Guidance:** Semantic tags guide developers in choosing appropriate HTML elements to represent different types of content, leading to clearer code and better component naming.
  5. **Future-proofing:** Semantic markup ensures that content remains meaningful and understandable even as web technologies evolve, ensuring compatibility and usability across different platforms and devices.
# What is JavaScript?

JavaScript is a scripting or programming language that enhances web pages with dynamic features, such as content updates, multimedia control, and interactive elements. It operates alongside HTML and CSS, forming a vital component of modern web development. JavaScript enables developers to manipulate the Document Object Model (DOM), handle events, and utilize Application Programming Interfaces (APIs) to create engaging user experiences. It executes in the browser environment, allowing for client-side code execution and dynamic content generation. Overall, JavaScript empowers developers to create interactive and dynamic web applications that go beyond displaying static information.

**2 things that require JavaScript in the Browser:**
1. **Form Validation:** JavaScript is commonly used to validate form inputs on web pages, ensuring that users enter data in the correct format before submission. This includes checking for required fields, validating email addresses, and verifying password strength.
   
2. **Dynamic Content:** JavaScript allows for the creation of interactive and dynamic content on web pages. This includes features such as sliders, image carousels, collapsible menus, and real-time updates without requiring a page refresh. 

**How to add JavaScript to an HTML document:**
JavaScript can be added to an HTML document in several ways:

1. **Inline Scripting:** JavaScript code can be included directly within the HTML document using the `<script>` tag with the `src` attribute pointing to an external JavaScript file or by embedding the code directly between `<script>` and `</script>` tags within the HTML document.

   Example:
   ```html
   <script>
       // JavaScript code here
   </script>
   ```

2. **External Script File:** JavaScript code can be placed in an external file with a `.js` extension and then linked to the HTML document using the `<script>` tag with the `src` attribute pointing to the external JavaScript file.

   Example:
   ```html
   <script src="script.js"></script>
   ```

3. **Event Handlers:** JavaScript code can be triggered by various events such as button clicks, form submissions, or page load events using event handlers like `onclick`, `onsubmit`, or `onload`.

   Example:
   ```html
   <button onclick="myFunction()">Click me</button>
   ```

4. **Asynchronous Loading:** JavaScript code can be loaded asynchronously to improve page loading performance by adding the `async` attribute to the `<script>` tag.

   Example:
   ```html
   <script src="script.js" async></script>
   ```

5. **Defer Loading:** JavaScript code can be deferred to execute after the HTML content has been parsed using the `defer` attribute in the `<script>` tag.

   Example:
   ```html
   <script src="script.js" defer></script>
   ```

## Things I Want to Know More About

- How does JavaScript handle things happening at the same time?
- Can JavaScript talk to databases directly on websites?
- Is JavaScript always safe to use on websites?