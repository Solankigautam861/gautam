## Module 1
-----------

1. **Are the HTML tags and elements the same thing?**
    - **Answer**: No, HTML tags and elements are not the same. Tags are the markup language components that create elements. An element consists of a start tag, content, and an end tag. For example:
      ```html
      <p>This is a paragraph.</p>
      ```
      - Here, `<p>` is a tag, and `<p>This is a paragraph.</p>` is an element.

2. **What are tags and attributes in HTML?**
    - **Answer**: Tags are used to create HTML elements. Attributes provide additional information about elements and are always included in the opening tag. For example:
      ```html
      <a href="https://www.example.com">This is a link</a>
      ```
        - In this example, `<a>` is the tag, and `href="https://www.example.com"` is an attribute that provides the URL the link points to.

3. **What are void elements in HTML? With Example.**
    - **Answer**: Void elements are HTML elements that do not have closing tags and cannot have any content. Examples include:
      ```html
      <img src="image.jpg" alt="Image description">
      <br>
      <input type="text" name="name">
      ```
        - Here, `<img>`, `<br>`, and `<input>` are void elements.

4. **What are HTML Entities? With Example.**
    - **Answer**: HTML entities are used to display reserved characters in HTML. For example, the less-than sign `<` is written as `&lt;`, and the ampersand `&` is written as `&amp;`. Example usage:
      ```html
      5 &lt; 10
      ```
        - This will display as `5 < 10`.

5. **What are different types of lists in HTML? With Example.**
    - **Answer**: There are three types of lists in HTML:
      - **Ordered list** (`<ol>`): 
        ```html
        <ol>
          <li>Item 1</li>
          <li>Item 2</li>
        </ol>
        ```
      - **Unordered list** (`<ul>`): 
        ```html
        <ul>
          <li>Item 1</li>
          <li>Item 2</li>
        </ul>
        ```
      - **Description list** (`<dl>`): 
        ```html
        <dl>
          <dt>Term 1</dt>
          <dd>Description 1</dd>
          <dt>Term 2</dt>
          <dd>Description 2</dd>
        </dl>
        ```

6. **What is the ‘class’ attribute in HTML? With Example.**
    - **Answer**: The `class` attribute is used to define a class for an HTML element, which can be styled with CSS or manipulated with JavaScript. Example:
      ```html
      <div class="container">This is a container</div>
      <p class="text">This is some text</p>
      ```
        - Here, both elements can be styled using the same CSS class.

7. **What is the difference between the ‘id’ attribute and the ‘class’ attribute of HTML elements? With Example.**
    - **Answer**: The `id` attribute uniquely identifies an HTML element, whereas the `class` attribute can be used to identify multiple elements. Example:
      ```html
      <div id="uniqueElement">Unique element</div>
      <div class="commonElement">Common element 1</div>
      <div class="commonElement">Common element 2</div>
      ```
        - The `id` should be unique within the document, while `class` can be shared by multiple elements.

8. **What are the various formatting tags in HTML?**
    - **Answer**: Some common formatting tags include:
      - `<b>` or `<strong>` for bold text
      - `<i>` or `<em>` for italic text
      - `<u>` for underlined text
      - `<mark>` for highlighted text
      - `<small>` for smaller text
      - `<del>` for strikethrough text
      - `<sub>` for subscript
      - `<sup>` for superscript Example:

        ```html
        <b>Bold text</b>
        <i>Italic text</i>
        <u>Underlined text</u>
        ```

9. **How is Cell Padding different from Cell Spacing? With Example.**
    - **Answer**: Cell padding is the space between the cell content and its borders, while cell spacing is the space between cells. For an Example;
      ```html
      <table border="1" cellpadding="10" cellspacing="5">
        <tr>
          <td>Cell 1</td>
          <td>Cell 2</td>
        </tr>
      </table>
      ```
        - Here, `cellpadding` adds space inside the cell, and `cellspacing` adds space between cells.

10. **How can we club two or more rows or columns into a single row or column in an HTML table? With Example.**
    - **Answer**: Use the `rowspan` attribute to merge rows and `colspan` to merge columns. Example:
      ```html
      <table border="1">
        <tr>
          <td rowspan="2">Rowspan</td>
          <td>Cell 2</td>
        </tr>
        <tr>
          <td>Cell 3</td>
        </tr>
        <tr>
          <td colspan="2">Colspan</td>
        </tr>
      </table>
      ```
        - Sure, I’ll answer these questions and provide examples where relevant.

11. **What is the difference between a block-level element and an inline element?**
    - **Block-level elements** take up the full width available, starting on a new line and stacking vertically. Examples include `<div>`, `<h1>` to `<h6>`, `<p>`, and `<section>`.
    - **Inline elements** take up only as much width as necessary and do not start on a new line. They stack horizontally with other inline elements. Examples include `<span>`, `<a>`, `<strong>`, and `<em>`.

12. **How to create a Hyperlink in HTML? With Example.**
    - **Answer**:To create a hyperlink in HTML, use the `<a>` tag with the `href` attribute specifying the URL.
      ```html
      
      <a href=<https://www.example.com>>Visit Example</a>
      
      ```
      
13. **What is the use of an iframe tag? With Example.**
    - **Answer**:The `<iframe>` tag is used to embed another HTML page within the current page. Example:
      ```html
      
      <iframe src=<https://www.example.com> width=”600” height=”400”></iframe>
      
      ```
      
14. **What is the use of a span tag? Explain with example?**
    - **Answer**:The `<span>` tag is used to apply styles or perform actions on a specific part of text without disrupting the flow of content, as it is an inline element. Example:
      ```html
      
      <p>This is a <span style=”color: red;”>red</span> word in a sentence.</p>
      
      ```
      
15. **How to insert a picture into a background image of a web page? With Example.**
    - **Answer**:To insert a picture as a background image, use CSS to set the `background-image` property. Example:
      ```html
      <!DOCTYPE html>
      <html>
      <head>
      <style>
      Body {
          Background-image: url(‘background.jpg’);
          Background-size: cover;
      }
      </style>
      </head>
      <body>
          <h1>Welcome to My Website</h1>
      </body>
      </html>
      ```
      
16. **How are active links different from normal links?**
    - **Answer**:Active links are those that are currently being clicked or are in the process of being clicked, often styled differently using the `:active` pseudo-class in CSS. Normal links are in their default, unvisited state.
    Example:
      ```html
      <style>
      A:link {
          Color: blue;
      }
      A:active {
          Color: red;
      }
      </style>
      <a href=<https://www.example.com>>Example Link</a>
      ```

17. **What are the different tags to separate sections of text?**
    - **Answer**:Several tags can be used to separate sections of text in HTML:
      - `<div>`: Defines a division or section.
      - `<section>`: Defines a section in a document.
      - `<article>`: Defines an independent piece of content.
      - `<header>`: Defines a header for a section or page.
      - `<footer>`: Defines a footer for a section or page.
      - `<nav>`: Defines navigation links.
      - `<aside>`: Defines content aside from the main content.
      - `<br>`: Inserts a line break.
      - `<hr>`: Inserts a thematic break (horizontal rule).
      
18. **What is SVG?**
    - **Answer**:SVG (Scalable Vector Graphics) is an XML-based format for vector images, which can be scaled infinitely without losing quality. It is used for defining graphics in HTML.
    Example:
      ```html
      <svg width=”100” height=”100”>
          <circle cx=”50” cy=”50” r=”40” stroke=”black” stroke-width=”3” fill=”red” />
      </svg>
      ```

19. **What is the difference between HTML and XHTML?**
    - **Answer**:**HTML (HyperText Markup Language)** is more lenient in syntax and does not always require strict closing of tags or case sensitivity.
    - **XHTML (Extensible HyperText Markup Language)** is stricter and follows XML syntax rules. All tags must be closed, nested properly, and written in lowercase.
    Example differences:
      - HTML: `<img src=”image.jpg”>`
      - XHTML: `<img src=”image.jpg” />`

