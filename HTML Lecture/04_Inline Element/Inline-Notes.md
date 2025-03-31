# **📖 Understanding Inline Elements in HTML**  

## **🔹 What Are Inline Elements?**  
Inline elements are **HTML elements that do not start on a new line** and only take up as much width as necessary. They are used for formatting text inside a paragraph or other inline content.  

Unlike **block elements** (like `<p>`, `<div>`, and `<h1>`), which take up the full width of their parent container, **inline elements** only occupy the space they need.  

---

## **🔹 Common Inline Elements in HTML**  
Here are some important inline elements with their uses:  

| **Tag** | **Description** | **Example** |
|---------|---------------|------------|
| `<sub>` | Subscript text (used in chemical formulas, math expressions, etc.) | `H<sub>2</sub>O` → H₂O |
| `<sup>` | Superscript text (used for exponents, footnotes, etc.) | `5<sup>2</sup>` → 5² |
| `<u>` | Underlined text (not recommended for emphasis; use `<em>` instead) | `<u>Important Text</u>` → **Important Text** |
| `<ins>` | Inserted text (usually underlined, indicating additions) | `<ins>New content</ins>` → **New content** |
| `<del>` | Deleted text (usually shown with a strikethrough, indicating removed content) | `<del>Removed text</del>` → ~~Removed text~~ |
| `<s>` | Strikethrough text (used for outdated or irrelevant content) | `<s>Old price: $100</s> New price: $80` → ~~Old price: $100~~ New price: $80 |
| `<mark>` | Highlighted text (used to emphasize text like a highlighter) | `<mark>Important</mark>` → **Important** |

---

## **🔹 Practical Examples of Inline Elements**  
### **Subscript & Superscript**
Subscript `<sub>` is commonly used in chemical formulas, and superscript `<sup>` is used for exponents:  
```html
<p>Water formula: H<sub>2</sub>O</p>
<p>Mathematical power: 5<sup>2</sup> = 25</p>
```
🔹 **Output:**  
Water formula: **H₂O**  
Mathematical power: **5² = 25**  

---

### **Underlined & Inserted Text**
Underlining is done using `<u>`, and inserted text (which is usually underlined) is done using `<ins>`:  
```html
<p>This is a <u>underlined</u> word.</p>
<p>This is <ins>newly inserted</ins> content.</p>
```
🔹 **Output:**  
This is a **underlined** word.  
This is **newly inserted** content.  

---

### **Deleted & Strikethrough Text**
Both `<del>` and `<s>` create strikethrough effects, but `<del>` is for content that was removed, while `<s>` is for content that is outdated:  
```html
<p>Original Price: <del>$100</del> Discounted Price: $80</p>
<p>Old Product Name: <s>XYZ Phone</s> New Name: ABC Phone</p>
```
🔹 **Output:**  
Original Price: ~~$100~~ Discounted Price: **$80**  
Old Product Name: ~~XYZ Phone~~ New Name: **ABC Phone**  

---

### **Highlighting Text**
The `<mark>` tag is used for **highlighting important text**:  
```html
<p>Please remember to <mark>submit your assignment</mark> before Friday.</p>
```
🔹 **Output:**  
Please remember to **submit your assignment** before Friday.  

---

## **🔹 Differences Between Inline & Block Elements**
| Feature | **Inline Elements** | **Block Elements** |
|---------|------------------|----------------|
| **Starts on a new line?** | ❌ No | ✅ Yes |
| **Takes full width?** | ❌ No (only as wide as the content) | ✅ Yes (fills the parent container) |
| **Common Examples** | `<span>`, `<a>`, `<img>`, `<strong>`, `<em>` | `<div>`, `<p>`, `<h1>`, `<section>` |

Example of **block** vs **inline** elements:  
```html
<p>This is a paragraph (block element).</p>
<span>This is a span (inline element).</span>
```
🔹 **Output:**  
The `<p>` tag takes the full width and starts on a new line.  
The `<span>` tag does **not** start on a new line.  

---

## **🔹 Best Practices for Using Inline Elements**
✅ **Use `<strong>` and `<em>` for emphasis** instead of `<b>` and `<i>` because they add meaning to the text.  
✅ **Avoid `<u>` for emphasis** since underlined text is usually associated with links.  
✅ **Use `<mark>` for highlighting important text**, but don’t overuse it.  
✅ **Be mindful of `<s>` and `<del>`**—they should be used to indicate outdated or removed text.  

---

## **🔹 Note:**
- Inline elements **stay on the same line** and take up only as much space as needed.  
- Common inline elements include `<sub>`, `<sup>`, `<u>`, `<ins>`, `<del>`, `<s>`, and `<mark>`.  
- Understanding the difference between **inline and block elements** is crucial for proper HTML structuring.  

