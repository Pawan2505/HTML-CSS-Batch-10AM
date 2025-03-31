# **Online Images in HTML**  

## **1. What are Online Images?**  
Online images are images that are **hosted on the internet** instead of being stored on your local computer. They have a **URL (link)** that allows you to access them from anywhere.  

Example of an online image URL:  
`https://picsum.photos/id/232/500/300`  

This means the image is coming from a website (in this case, `picsum.photos`), and the browser fetches it when loading the page.  

---

## **2. Basic HTML Structure for Images**
Here’s a simple breakdown of the code:  

```html
<img src="IMAGE_URL_HERE" alt="Description of image">
```
- `src`: This is the **source URL** of the image.  
- `alt`: The **alternative text** shown if the image doesn’t load (important for accessibility & SEO).  

Example:  
```html
<img src="https://picsum.photos/id/232/500/300" alt="Random image from Picsum">
```
---

## **3. Full Code Breakdown**  
Now, let’s go step by step through the given code:  

### **Head Section**
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Image</title>
</head>
```
✅ The `<meta>` tags ensure the page displays correctly on all devices.  
✅ `<title>` sets the name of the page (shown in the browser tab).  

---

### **Body Section**
```html
<body>
    <div>
        <img src="https://picsum.photos/id/232/500/300" alt="Random image from Picsum">
        <img src="https://i.pinimg.com/736x/89/78/01/897801247990dbfb657ddad0cdaa2305.jpg" width="800px" height="400px" alt="Beautiful Pinterest image">
    </div>
</body>
```
✅ **First Image** loads a random image from Picsum with a default size of `500x300px`.  
✅ **Second Image** is from Pinterest, but this time we manually set the width to `800px` and height to `400px`.  

---

## **4. Best Practices for Using Online Images**  
### ✅ Use Proper `alt` Text  
Always add a meaningful `alt` description for accessibility.  

### ✅ Use Responsive Images  
Instead of fixed `width` and `height`, use CSS to make images **responsive**.  
Example:
```css
img {
    max-width: 100%;
    height: auto;
}
```
This ensures images adjust to different screen sizes automatically.  

### ✅ Avoid Broken Links  
Make sure the image URL is correct! If the image is deleted or moved, it won’t load.  

---
