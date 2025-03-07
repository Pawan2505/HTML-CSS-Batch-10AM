### **HTML List Elements Build Notes**

#### **1. Ordered List (`<ol>`)**

- An **ordered list** is used to display a list of items in a specific order. The items are marked with numbers or letters by default.

##### **Key Attributes:**

- **`type`**: Defines the type of numbering:
  - **`type="1"`**: Default numeric list (1, 2, 3, …).
  - **`type="A"`**: Uppercase letters (A, B, C, …).
  - **`type="a"`**: Lowercase letters (a, b, c, …).
  - **`type="I"`**: Uppercase Roman numerals (I, II, III, …).
  - **`type="i"`**: Lowercase Roman numerals (i, ii, iii, …).
- **`start`**: Specifies the starting number for the list. For example, `start="50"` will start the list from number 50.

##### **Example:**

```html
<ol type="A" start="10">
  <li>First item</li>
  <li>Second item</li>
</ol>
```

This will create an ordered list starting with "A" and starting from number 10.

#### **2. Unordered List (`<ul>`)**

- An **unordered list** is used to display a list of items where the order does not matter. The items are marked with bullets by default.

##### **Key Attributes:**

- **`type`**: Defines the bullet style:
  - **`type="disc"`**: Default style (solid circle).
  - **`type="circle"`**: Hollow circle.
  - **`type="square"`**: Square bullets.
  - **`type="none"`**: No bullets (useful for custom styling with CSS).
- **`align`**: This attribute is used to align the list. Common values are `start`, `center`, and `end`.

##### **Example:**

```html
<ul type="circle" align="center">
  <li>First item</li>
  <li>Second item</li>
</ul>
```

This creates an unordered list with circle bullets and centered alignment.

#### **3. Description List (`<dl>`)**

- A **description list** is used to pair a term (`<dt>`) with its description (`<dd>`).

##### **Structure:**

- **`<dt>`**: Defines the term or topic.
- **`<dd>`**: Provides the description or definition for the term.

##### **Example:**

```html
<dl>
  <dt>HTML</dt>
  <dd>
    HTML stands for Hypertext Markup Language. It is used to create web pages.
  </dd>
  <dt>CSS</dt>
  <dd>CSS stands for Cascading Style Sheets. It is used to style web pages.</dd>
</dl>
```

This will display the terms "HTML" and "CSS" with their respective definitions.

#### **4. Note:**

- **Ordered lists** are great when the sequence of items matters (e.g., steps in a process).
- **Unordered lists** are used when the order doesn't matter (e.g., a list of items or features).
- **Description lists** are useful when you need to define terms or provide more detailed explanations.
- Experiment with different **`type`** attributes in both ordered and unordered lists to familiarize yourself with how these attributes change the look and feel of the lists.

#### **Useful Resources**

- [MDN Web Docs - Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
- [W3Schools - HTML Lists](https://www.w3schools.com/html/html_lists.asp)

---
