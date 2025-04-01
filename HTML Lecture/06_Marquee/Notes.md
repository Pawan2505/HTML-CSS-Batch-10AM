# **HTML `<marquee>` Tag**

## **Introduction**
The `<marquee>` tag in HTML is used to create scrolling text or images on a web page. It moves content automatically in a specified direction. 

> **Note:** The `<marquee>` tag is *deprecated* in HTML5, meaning it is no longer recommended for use in modern web development. However, it still works in most browsers.

---

## **Syntax of `<marquee>` Tag**
```html
<marquee>Scrolling Text</marquee>
```
This creates a simple scrolling text.

---

## **Attributes of `<marquee>`**

The `<marquee>` tag has several attributes that control its behavior:

| Attribute | Description | Example |
|-----------|------------|---------|
| `direction` | Defines the scrolling direction. Values: `left`, `right`, `up`, `down`. | `<marquee direction="right">Moving Right</marquee>` |
| `behavior` | Defines the type of movement. Values: `scroll`, `slide`, `alternate`. | `<marquee behavior="alternate">Bouncing Text</marquee>` |
| `scrollamount` | Defines the speed of the scrolling text. (Higher value = faster) | `<marquee scrollamount="10">Fast Scrolling</marquee>` |
| `bgcolor` | Sets the background c olor of the marquee. | `<marquee bgcolor="yellow">Yellow Background</marquee>` |
| `width` | Defines the width of the marquee (in px or %). | `<marquee width="50%">Half Width</marquee>` |
| `height` | Defines the height of the marquee (in px or %). | `<marquee height="50">50px Height</marquee>` |

---

## **Examples**

### 1. **Basic Scrolling Text**
```html
<marquee>Welcome to Web Development!</marquee>
```

### 2. **Scrolling in Different Directions**
```html
<marquee direction="right">Moving Right</marquee>
<marquee direction="up">Moving Up</marquee>
<marquee direction="down">Moving Down</marquee>
```

### 3. **Different Behaviors**
```html
<marquee behavior="scroll">Normal Scroll</marquee>
<marquee behavior="slide">Slides Once</marquee>
<marquee behavior="alternate">Bounces Back</marquee>
```

### 4. **Fast and Slow Scrolling**
```html
<marquee scrollamount="20">Fast Scroll</marquee>
<marquee scrollamount="2">Slow Scroll</marquee>
```

### 5. **Marquee with Background Color**
```html
<marquee bgcolor="lightblue">Colored Background</marquee>
```

### 7. **Marquee with Image**
```html
<marquee direction="left">
    <img src="example.jpg" width="100" height="50">
</marquee>
```

---

## **Note:**
- The `<marquee>` tag is useful for adding movement to text and images.
- It is outdated and replaced by CSS animations (`@keyframes` and `animation`).
- Use it carefully, as excessive movement can be distracting.
