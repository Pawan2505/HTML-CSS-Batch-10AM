### **Lecture Notes: Introduction to HTML - Basic Structure and Elements**

---

### **What is HTML?**

- **HTML** stands for **Hypertext Markup Language**.
- It is the standard language used to create and design webpages.
- HTML uses **tags** to tell the browser how to display content on a page.
  
---

### **HTML File Structure**

An HTML file typically consists of the following parts:

1. **DOCTYPE Declaration**: Tells the browser what version of HTML is being used (HTML5 is the latest).
   ```html
   <!DOCTYPE html>
   ```

2. **HTML Tags**: Everything in HTML is wrapped in `<html>` tags.
   ```html
   <html>
       <!-- Content goes here -->
   </html>
   ```

3. **Head Section**: Contains information about the webpage, like its title and link to stylesheets or scripts.
   ```html
   <head>
       <title>My Webpage</title>
   </head>
   ```

4. **Body Section**: Contains the visible content on the webpage (headings, paragraphs, images, etc.).
   ```html
   <body>
       <!-- Visible content goes here -->
   </body>
   ```

---

### **HTML Elements and Tags**

- **Tags**: HTML tags tell the browser how to display content. Tags usually come in pairs, with an opening tag (`<tag>`) and a closing tag (`</tag>`). The content goes between these tags.

---

### **Common HTML Tags**

#### **1. Headings**
- Headings are used to define titles or subtitles. There are 6 levels of headings, from `<h1>` (largest) to `<h6>` (smallest).
  
Example:
```html
<h1>This is the largest heading</h1>
<h2>This is a smaller heading</h2>
```

---

#### **2. Paragraphs**
- Paragraphs are created using the `<p>` tag. It is used to display blocks of text.

Example:
```html
<p>This is a paragraph of text. Paragraphs are used to display written content.</p>
```

---

#### **3. Preformatted Text**
- The `<pre>` tag is used when you want to display text exactly as it is written, including spaces and new lines.

Example:
```html
<pre>
    This text
    will be displayed
    exactly as it is
    written in the code.
</pre>
```

---

#### **4. Line Breaks and Horizontal Line**
- **Line Break**: The `<br/>` tag creates a line break in text, pushing the content to the next line.
  
Example:
```html
<p>This is some text.<br/>This text appears below the first one.</p>
```

- **Horizontal Line**: The `<hr/>` tag creates a horizontal line across the page to separate content visually.

Example:
```html
<hr/>
```

---

#### **5. Lists**
HTML allows you to create different types of lists:
  
- **Ordered List**: Displays items with numbers (1, 2, 3, etc.).
  ```html
  <ol>
      <li>First item</li>
      <li>Second item</li>
      <li>Third item</li>
  </ol>
  ```

- **Unordered List**: Displays items with bullet points (•).
  ```html
  <ul>
      <li>Apple</li>
      <li>Banana</li>
      <li>Cherry</li>
  </ul>
  ```

- **Description List**: A list where each item has a term and description.
  ```html
  <dl>
      <dt>HTML</dt>
      <dd>HTML stands for Hypertext Markup Language.</dd>
      <dt>CSS</dt>
      <dd>CSS is used to style HTML content.</dd>
  </dl>
  ```

---

### **Attributes in HTML Tags**

- **Attributes** provide additional information about an element, such as its type, color, size, and position.
  
Example:
```html
<a href="https://www.example.com">Visit Example</a>
```
Here, `href` is an attribute that tells the browser where the link goes.

---

### **Key HTML Tags to Remember**

1. **`<html>`**: The root element for the webpage.
2. **`<head>`**: Contains meta information like the title of the webpage.
3. **`<title>`**: Sets the title that appears on the browser tab.
4. **`<body>`**: Contains the content of the webpage.
5. **`<h1>` - `<h6>`**: Defines headings of different sizes.
6. **`<p>`**: Defines a paragraph.
7. **`<pre>`**: Preserves whitespace formatting (for code, poetry, etc.).
8. **`<br/>`**: Line break.
9. **`<hr/>`**: Horizontal line.
10. **`<ul>`**: Unordered list (bullets).
11. **`<ol>`**: Ordered list (numbers).
12. **`<li>`**: List item.
13. **`<a>`**: Anchor tag for creating links.
14. **`<img>`**: For displaying images.

---

### **Note:**

- HTML is used to create and structure content on the web.
- **Tags** and **attributes** define how content appears on a webpage.
- **Headings** organize content, and **paragraphs** display text.
- **Lists** help you present information in an organized way.
- HTML also supports adding **images**, **links**, and other multimedia content.

---

### **Practice Task**

Try creating a basic HTML webpage:
1. Add a heading with your name.
2. Write a paragraph introducing yourself.
3. Include an image of something you like.
4. Add a list of your favorite hobbies.

---
