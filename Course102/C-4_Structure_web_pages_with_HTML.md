# Structure web pages with HTML

1. **What is HTML and why do we use it?**
   - HTML, or HyperText Markup Language, is the standard language for creating web pages. It allows developers to structure content on a webpage, defining elements like text, images, links, and forms, forming the foundational structure of websites.

2. **What are the 3 main parts of an HTML element?** 
   1. `opening tag`, which marks the beginning of the element; 
   2. `content`the actual information or nested elements;
   3. `closing tag`, indicating the end of the element. 

- **Example:** `<p>This is a paragraph.</p>`

- This structure, represented as opening tag, content, and closing tag, forms the basic syntax of HTML elements.

3. **What is it called when you give an element extra information?**
   - Providing extra information to an HTML element is called adding attributes. Attributes, included within the opening tag, offer additional details or modifications to the element, enhancing its behavior or appearance.
   - `href` is  attribute specifies the hyperlink reference or URL to which the anchor element links. 

- **Example:** `<a href="https://www.example.com">Visit Example.com</a>`

4. **semantic element?**
   - A semantic element in HTML conveys meaning about the structure and content of a document to both browsers and developers. Elements like `<header>`, `<footer>`, and `<article>` provide clarity and improve the readability of HTML by indicating the role and significance of different parts of a webpage.

## **Wireframe:**
- A wireframe is a visual representation or skeletal outline of a web page or interface. It outlines the basic structure and layout without detailing design elements, helping to plan the arrangement of content.

![Wireframe Example](https://d3mm2s9r15iqcv.cloudfront.net/en/wp-content/uploads/old-blog-uploads/versions/samuel-student-wireframe---x----972-715x---.png)

## **Element:**
- An HTML element is a building block of a webpage, defined by tags. It consists of an opening tag, content, and a closing tag, representing different types of content such as paragraphs, headings, images, etc.

## **Tag:**
- Tags are markers used in HTML to define elements. They consist of an opening tag (e.g., `<p>`) and a closing tag (e.g., `</p>`), with content in between. Tags structure and organize content on a webpage.

## **Attribute:**
- Attributes provide additional information about HTML elements. They are included within the opening tag and modify the behavior or appearance of the element. For example, the `src` attribute in an `<img>` tag specifies the image source.

## **Structure vs Presentation:**
- Structure refers to the organization and arrangement of content on a webpage, defining the relationships between different elements. Presentation involves the styling and visual aspects of the content, typically handled by CSS (Cascading Style Sheets). It is a best practice to separate structure (HTML) from presentation (CSS) for maintainability and flexibility in web development.

## **Usefull Tools**

Wireframe tools:
- InVision
- Wireframe.cc
- UXPin
- Google Draw

Making Links: `<a></a> - element` 
```
<a href="https://github.com">GitHub</a>
```
<a href="https://github.com">GitHub</a>

Starting a HTML file for a Website

```
> <!DOCTYPE html>
> <html>
> <head>
>    <title>Your Website Title</title>
> </head>
> <body>

> <!-- Your content goes here -->

> </body>
> </html>
```
