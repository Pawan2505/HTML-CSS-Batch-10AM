#### 1. **HTML Document Structure**

An HTML document has a specific structure that starts with the `<html>` tag and ends with the `</html>` tag. 

```html
<html>
   <!-- Content goes here -->
</html>
```

- The `<html>` tag is the root element that contains the entire HTML document.
- Inside the `<html>` tag, there are two main sections:
  - **`<head>`**: Contains metadata about the document (like the title, links to CSS, etc.).
  - **`<body>`**: Contains the content that will be visible to the user on the webpage.

#### 2. **The `<head>` Section**
The `<head>` section holds the document's metadata, such as the title of the webpage, links to external resources like CSS stylesheets, and scripts. 

```html
<head>
    <title>First Class Of HTML</title>
</head>
```

- **`<title>`**: The title element specifies the title of the document, which will be shown in the browser’s tab.

#### 3. **The `<body>` Section**
The `<body>` section contains all the visible content of the webpage. This is where you'll add headings, paragraphs, images, links, and other elements.

#### 4. **Headings in HTML**

Headings are used to organize and structure content on a webpage. HTML provides six levels of headings, from `<h1>` (largest) to `<h6>` (smallest).

```html
<h1>First Heading</h1>
<h2>Second Heading</h2>
<h3>Third Heading</h3>
<h4>Fourth Heading</h4>
<h5>Fifth Heading</h5>
<h6>Sixth Heading</h6>
```

- `<h1>` is used for the main heading, typically the most important heading.
- `<h2>` through `<h6>` are used for subheadings, decreasing in size and importance as the number increases.

#### 5. **Block-Level Elements**

Block-level elements take up the full width of their container and always start on a new line. They are often used for larger sections of content such as headings, paragraphs, and divs.

**Examples of Block-Level Elements**:
- Headings (`<h1>`, `<h2>`, `<h3>`, etc.)
- Paragraphs (`<p>`)
- Divisions (`<div>`)

**Characteristics**:
- They start on a new line.
- They take up the entire width available.

```html
<h1>Example of a block-level element</h1>
```

#### 6. **Inline-Level Elements**

Inline elements are used for smaller portions of content and do not cause a new line to start. They only take up as much width as necessary for their content.

**Examples of Inline-Level Elements**:
- `<span>`
- `<a>` (anchor links)
- `<img>` (images)

**Characteristics**:
- They do not start on a new line.
- They only take up as much width as required by their content.

```html
<span>Hello</span>
<span>World</span>
```

In this example, "Hello" and "World" appear on the same line.

#### 7. **Case Sensitivity in HTML**

HTML tags are not case-sensitive. You can write tag names in uppercase, lowercase, or a mix of both. However, it is best practice to use lowercase to maintain consistency and readability.

```html
<!-- Both are valid -->
<H1>First Heading</H1>
<h1>First Heading</h1>
```

#### 8. **Final Notes**

- HTML tags define the structure of a webpage. Tags are always enclosed in angle brackets `< >`.
- Comments in HTML are written using `<!-- comment -->` and help to add notes without affecting the page output.

#### 9. **Additional Learning Resources**
For more detailed tutorials, you can check out this helpful YouTube video:
- [HTML Tutorial Video](https://www.youtube.com/watch?v=lzuiuRgwwrc)

---
