# **HTML `<a>` (Anchor) Tag**

## **Introduction**
The `<a>` tag in HTML is used to create hyperlinks. It allows users to click and navigate to another webpage, a specific section within the same page, an email address, or a file.

### **Basic Syntax**
```html
<a href="URL">Clickable Text</a>
```
- The `href` attribute defines the destination (link).
- The text inside the `<a>` tag is what users click on.

---

## **Types of Links**

### **1. Linking to Another Website**
```html
<a href="https://www.google.com">Go to Google</a>
```
- This opens Google when clicked.

### **2. Linking to Another Page in the Same Website**
```html
<a href="about.html">About Us</a>
```
- This opens `about.html`, assuming it is in the same folder.

### **3. Linking to a Section in the Same Page (Jump Link)**
You can create a jump link within the same page using the `id` attribute.

```html
<a href="#section2">Go to Section 2</a>

<h2 id="section2">This is Section 2</h2>
```
- Clicking the link will scroll down to Section 2.

### **4. Opening a Link in a New Tab**
Use the `target="_blank"` attribute to open a link in a new tab.

```html
<a href="https://www.wikipedia.org" target="_blank">Open Wikipedia in New Tab</a>
```

### **5. Creating an Email Link**
You can create a link that opens the user's email app.

```html
<a href="mailto:someone@example.com">Send Email</a>
```
- Clicking this opens the email client with the recipient's address pre-filled.

### **6. Creating a Phone Call Link**
You can create a clickable phone number.

```html
<a href="tel:+1234567890">Call Us</a>
```
- On mobile devices, this dials the number automatically.

### **7. Linking to a Downloadable File**
You can link to a file for downloading.

```html
<a href="document.pdf" download>Download PDF</a>
```
- Clicking this starts the download.

---

## **Example: Full Webpage Using `<a>` Tag**
```html
<!DOCTYPE html>
<html>
<head>
    <title>Anchor Tag Example</title>
</head>
<body>

    <h1>Welcome to My Website</h1>

    <p>Click the link below to visit Google:</p>
    <a href="https://www.google.com" target="_blank">Go to Google</a>

    <p>Jump to the bottom of the page:</p>
    <a href="#bottom">Go to Bottom</a>

    <h2 id="bottom">You are at the bottom!</h2>

</body>
</html>
```

---

## **Note:**
- The `<a>` tag is essential for navigation in HTML.
- Use `href` to define the destination.
- `target="_blank"` opens in a new tab.
- It can be used for links, email, phone calls, downloads, and more.