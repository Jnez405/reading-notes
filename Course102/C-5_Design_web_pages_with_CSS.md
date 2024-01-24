
# Design web pages with CSS

## **CSS Purpose**
**CSS (Cascading Style Sheets)** serves as a styling language for web documents, enabling the separation of content from presentation. It defines the visual appearance of HTML and XML elements, enhancing the design and user experience of websites.

- Defines the presentation of a document written in HTML or XML.
- Allows for separation of content and presentation.
- Enhances the visual appeal of a webpage.

## **Ways to Insert CSS**

**1. Inline CSS:**
```html
<p style="color: red;">This is a red paragraph.</p>
```

**2. Internal CSS:**
```html
<head>
  <style>
    p {
      color: blue;
      font-size: 16px;
    }
  </style>
</head>
```

**3. External CSS:**

You need to save a .css file that has the formatting for the text, then add tags to pull what you need from the .css file to you HTML file 

In "styles.css" file:
```css
/* styles.css */
p {
  color: green;
  font-family: 'Arial', sans-serif;
}
```

In HTML file:
```html
<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
```

## A CSS rule that would give all `<p>` elemnts red text

```
p {
  color: red;
}
```



<!-- 
What is the purpose of CSS?
What are the three ways to insert CSS into your project?
Write an example of a CSS rule that would give all <p> elements red text 
-->
