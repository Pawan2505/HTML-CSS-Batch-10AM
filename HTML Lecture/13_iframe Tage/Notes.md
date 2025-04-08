## 📒 `<iframe>` Tag

---

### 🔹 What is `<iframe>`?

- **iframe** stands for **inline frame**  
- It is used to **show another website** inside your web page  
- Example: Google Map, YouTube video, another HTML page

---

### 🔹 Syntax:

```html
<iframe src="URL" width="..." height="..."></iframe>
```

---

### 🔹 Common Attributes:

| Attribute        | Meaning |
|------------------|---------|
| `src`            | Link of the content (website, video, map) |
| `width` & `height` | Size of the iframe box |
| `frameborder`    | Border of the iframe (0 = no border) |
| `allowfullscreen`| Allows full-screen (for videos) |
| `loading="lazy"` | Loads only when needed (improves speed) |

---

### 🔹 Examples:

#### 👉 Google Map Embed:

```html
<iframe 
  src="https://www.google.com/maps/..."
  width="600" 
  height="350">
</iframe>
```

#### 👉 YouTube Video Embed:

```html
<iframe 
  src="https://www.youtube.com/embed/xyz"
  width="560" 
  height="315"
  allowfullscreen>
</iframe>
```

---

### ✅ Use of `<iframe>`:

- To show **videos** (like YouTube)
- To display **locations/maps** (Google Maps)
- To embed **forms, PDFs, other web pages**
