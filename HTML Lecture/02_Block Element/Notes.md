### **HTML Block-Level Elements**

**block-level elements**, which typically start on a new line and take up the full width of the container.

---

#### **1. Block-Level Elements:**

Block-level elements are usually used to define sections of content on a webpage. Examples include:

- **Headings**: `<h1>` to `<h6>`
- **Paragraph**: `<p>`
- **Lists**: `<ul>`, `<ol>`, `<li>`
- **Horizontal Rule**: `<hr />`
- **Preformatted Text**: `<pre>`

---

#### **2. Key Block-Level Elements in Action:**

- **Heading Tags `<h1>` to `<h6>`**  
  These tags are used to create headings, with `<h1>` being the most important and largest.

```html
<h1 align="center">Paragraph</h1> <!-- Largest heading, centered -->
```

- **Paragraph Tag `<p>`**  
  Used to define a paragraph. Text inside the `<p>` tag is displayed as a block, and it can include line breaks using `<br />`.

```html
<p>
    Lorem ipsum dolor sit amet consectetur.
    <br /> <!-- Line break -->
    Labore aut aliquid illo.
</p>
```

- **Horizontal Rule `<hr />`**  
  Creates a horizontal line, often used to separate content visually.

```html
<hr />
```

- **Preformatted Text `<pre>`**  
  The text inside this tag preserves spaces and line breaks, useful for code or poetry.

```html
<pre>
The City Sleeps
The city sighs, a gentle hum,
...
</pre>
```

---

#### **3. Lists in HTML:**

- **Ordered List (`<ol>`)**: Lists with numbered items.
- **Unordered List (`<ul>`)**: Lists with bullet points.
- **Description List (`<dl>`)**: A list of terms and their descriptions.

Examples of **ordered** lists (numbered):

```html
<ol>
    <li>Apple</li>
    <li>Banana</li>
</ol>

<ol type="A">
    <li>Apple</li>
    <li>Banana</li>
</ol>

<ol type="i">
    <li>Apple</li>
    <li>Banana</li>
</ol>
```

Examples of **unordered** lists (bullet points):

```html
<ul type="disc">
    <li>Apple</li>
    <li>Banana</li>
</ul>

<ul type="circle">
    <li>Apple</li>
    <li>Banana</li>
</ul>

<ul type="square">
    <li>Apple</li>
    <li>Banana</li>
</ul>

<ul type="none" align="center">
    <li>Apple</li>
    <li>Banana</li>
</ul>
```

---

#### **Note:**

- **Block-level elements** like headings, paragraphs, and lists structure your content on a webpage.
- **Headings (`<h1>` to `<h6>`)** help define sections of content.
- **Paragraphs (`<p>`)** group related text.
- **Lists** organize content into ordered or unordered formats.
- **Line breaks** (`<br />`) and **horizontal rules** (`<hr />`) help format the page.

This basic understanding of block-level elements will help you create well-structured and organized webpages.