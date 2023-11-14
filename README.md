## HTML tags for reference

1. `<!DOCTYPE>`: This declaration defines the document type and version of HTML being used.

2. `<html>`: The root element that contains all other HTML elements on the page.

3. `<head>`: Contains meta-information about the document, such as the title and links to external resources.

4. `<title>`: Sets the title of the web page, which is displayed in the browser's title bar or tab.

5. `<meta>`: Provides metadata about the HTML document, such as character encoding and author information.

6. `<link>`: Used to link external resources, like CSS stylesheets, to the HTML document.

7. `<style>`: Defines inline CSS styles for specific elements on the page.

8. `<script>`: Used to include JavaScript code in the HTML document.

9. `<body>`: Contains the visible content of the web page, including text, images, and other elements.

10. `<h1>, <h2>, <h3>, <h4>, <h5>, <h6>`: Headings of decreasing importance, with `<h1>` being the most important and `<h6>` the least.

11. `<p>`: Represents a paragraph of text.

12. `<a>`: Creates hyperlinks to other web pages or resources.

13. `<img>`: Embeds images in the web page.

14. `<ul>`: Defines an unordered list, often used with `<li>` elements.

15. `<ol>`: Defines an ordered list, where list items are automatically numbered.

16. `<li>`: List item element, used within `<ul>` and `<ol>` to define individual list items.

17. `<div>`: A generic container element often used for grouping and styling content.

18. `<span>`: A generic inline container element for applying styles or scripting to a specific portion of text.

19. `<br>`: Inserts a line break, useful for breaking text onto the next line without starting a new paragraph.

20. `<hr>`: Creates a horizontal rule or line to separate content.

21. `<table>`: Defines a table, which can be populated with rows and cells.

22. `<tr>`: Represents a table row.

23. `<th>`: Defines a table header cell.

24. `<td>`: Represents a table data cell.

25. `<form>`: Used to create web forms for user input.

26. `<input>`: An input field within a form, used for text, checkboxes, radio buttons, etc.

27. `<button>`: A clickable button often used in forms.

28. `<textarea>`: A multiline text input field within a form.

29. `<label>`: Describes the purpose of an input element in a form.

30. `<select>`: Creates a dropdown list within a form.

31. `<option>`: Represents an option in a `<select>` dropdown

## Basic CSS Properties for Web Styling

1. **Size and Spacing:**
   - `width`: Controls the width of an element.
   - `height`: Controls the height of an element.
   - `margin`: Sets the outer margin of an element.
   - `padding`: Sets the inner padding of an element.

```css
.example-element {
    width: 200px;
    height: 100px;       
    margin: 10px;
    padding: 20px;
} 
```

2. **Text Styling:**
   - `font-size`: Sets the size of the text.
   - `font-family`: Defines the type of font.
   - `color`: Specifies the color of the text.

```css
.example-text {
    font-size: 16px;
    font-family: "Arial", sans-serif;
    color: #333;
}
```

3. **Layout:**
   - `display`: Defines how an element is displayed (block, inline, etc.).
   - `float`: Positions an element to the left or right within its container.
```css
.layout-container {
    display: flex;
    float: right;
}

```

4. **Positioning:**
   - `position`: Sets the positioning method (static, relative, absolute, fixed).
```css
.positioned-element {
    position: relative;
    top: 20px;
    left: 30px;
}
```

5. **Border and Box Model:**
   - `border`: Sets the border of an element.
   - `box-sizing`: Defines how the width and height of an element are calculated.
```css
.bordered-element {
    border: 1px solid #000;
    box-sizing: border-box;
}
```

6. **Background:**
   - `background-color`: Sets the background color of an element.
   - `background-image`: Sets the background image of an element.
```css
.background-element {
    background-color: #f0f0f0;
    background-image: url('background.jpg');
}
```

7. **Text Alignment:**
   - `text-align`: Aligns text within its container.
```css
.aligned-text {
    text-align: center;
}
```

8. **List Styling:**
   - `list-style-type`: Sets the style of list items.
```css
.styled-list {
    list-style-type: square;
}
```

9. **Link Styling:**
   - `text-decoration`: Removes underlines from links (commonly set to `none`).
   - `hover`: Changes the style when the mouse hovers over a link.
```css
.styled-link {
    text-decoration: none;
}
.styled-link:hover {
    color: #FF5733; /* Example color change on hover */
}
```

10. **Visibility:**
    - `display: none`: Hides an element.
```css
.hidden-element {
    display: none;
}
```

Remember, these basics provide a solid foundation for styling web pages. As you become more comfortable with these concepts, you can gradually explore more advanced properties and techniques.
