### **HTML Description List**

In HTML, a **description list** (`<dl>`) is used to display a list of terms and their associated descriptions. 

---

### **HTML Structure for a Description List:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"> <!-- Character encoding for proper display of special characters -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Makes the page mobile-friendly -->
    <title>Description List</title> <!-- Title displayed on the browser tab -->
</head>
<body>
    <!-- Description List: <dl> -->
    <dl>
        <!-- Definition Term: <dt> -->
        <dt>Term 1</dt>
        <!-- Definition Description: <dd> -->
        <dd>Description for Term 1.</dd>
        
        <dt>Term 2</dt>
        <dd>Description for Term 2.</dd>

        <dt>Term 3</dt>
        <dd>Description for Term 3.</dd>
    </dl>
</body>
</html>
```

---

### **Tags Used in a Description List:**

- **`<dl>`**: Defines the description list container.
- **`<dt>`**: Defines a **term** or name within the list.
- **`<dd>`**: Defines the **description** of the term.

Each term (`<dt>`) can have multiple descriptions (`<dd>`), but typically one description per term is used.

---

### **Explanation of the Code:**

1. **`<!DOCTYPE html>`**: Declares the document type, specifying that it is HTML5.
2. **`<html lang="en">`**: Specifies that the language of the document is English.
3. **`<meta charset="UTF-8">`**: Ensures that special characters (like accented letters) are displayed correctly.
4. **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Makes the webpage responsive, scaling it correctly on mobile devices.
5. **`<title>`**: The title that will appear in the browser tab.
6. **`<dl>`**: The description list itself.
7. **`<dt>`**: Each **term** or name in the list.
8. **`<dd>`**: The **description** of the term.

---

### **Example:**

You might use a description list for something like a glossary:

```html
<dl>
    <dt>HTML</dt>
    <dd>HTML stands for Hypertext Markup Language, the standard language for creating webpages.</dd>

    <dt>CSS</dt>
    <dd>CSS stands for Cascading Style Sheets, used to style and layout webpages.</dd>

    <dt>JavaScript</dt>
    <dd>JavaScript is a programming language used to make webpages interactive.</dd>
</dl>
```

This structure is ideal for organizing and displaying terms with their definitions in a clean, readable format.

---

### **Note:**

- Use the **`<dl>`** tag for description lists.
- Use **`<dt>`** for the term and **`<dd>`** for the definition.
- Description lists are perfect for glossaries, FAQs, and definitions.

This is a simple and effective way to display related terms and descriptions on your webpage!