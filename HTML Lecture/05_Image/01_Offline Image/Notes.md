# **Offline Images in HTML**  

## **Introduction**  
In this lesson, we will learn how to **display offline images in HTML**—images that are stored on your computer rather than loaded from the internet. We will also discuss important attributes like `src`, `alt`, `title`, `width`, and `height` to make our images more accessible and properly formatted.  

---

## **🔹 What Are Offline Images?**  
Offline images are stored **locally** on your computer inside a project folder. Instead of using an image URL from the internet, we use a file path to reference an image stored in our project directory.  

For example, the path below refers to an image stored inside the `image` folder of the current project:  
```html
<img src="image/img1.jpeg" alt="First Image">
```
This means that:
1. The `image` folder must exist in the same directory as the HTML file.  
2. The image file inside the `image` folder must be named **exactly** as specified (case-sensitive).  

---

## **🔹 Understanding the Code Step by Step**  

### **1️⃣ Head Section**
```html
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Offline Image</title>
</head>
```
✅ `<meta charset="UTF-8">` ensures all characters (including special ones) are displayed correctly.  
✅ `<meta name="viewport" content="width=device-width, initial-scale=1.0">` makes the page responsive on different screen sizes.  
✅ `<title>Offline Image</title>` sets the page title, which appears on the browser tab.  

---

### **2️⃣ Body Section**
The body contains **three images**, each inside a `<div>` (a container).  

#### **Image 1:**
```html
<div>
    <img 
        src="image/img1.jpeg" 
        width="500px" 
        height="400px" 
        title="First Image" 
        alt="This is the first image" 
    />
</div>
```
✅ `src="image/img1.jpeg"` → This tells the browser to load `img1.jpeg` from the `image` folder.  
✅ `width="500px" height="400px"` → This **fixes the image size** at `500x400` pixels.  
✅ `title="First Image"` → When you hover over the image, this text appears as a tooltip.  
✅ `alt="This is the first image"` → If the image fails to load, this text appears instead (important for accessibility).  

---

#### **Image 2 & Image 3:**  
The next two images follow the same pattern but refer to different files (`img2.jpeg` and `img3.jpeg`):  
```html
<div>
    <img 
        src="image/img2.jpeg" 
        width="500px" 
        height="400px" 
        title="Second Image" 
        alt="This is the second image" 
    />
</div>

<div>
    <img 
        src="image/img3.jpeg" 
        width="500px" 
        height="400px" 
        title="Third Image" 
        alt="This is the third image" 
    />
</div>
```
Each image has its own:
- **`src` (file path)**  
- **`title` (hover text)**  
- **`alt` (alternative description)**  

---

## **🔹 Best Practices for Using Offline Images**  

### ✅ 1. **Use Relative Paths for Images**  
A relative path (`image/img1.jpeg`) makes your project **portable**, meaning it will work on any computer as long as the folder structure remains the same.  

If you use an absolute path like:  
```html
<img src="C:/Users/YourName/Desktop/project/image/img1.jpeg">
```
It will **only work on your computer** but not on another person's system.  

---

### ✅ 2. **Use Descriptive `alt` Text**  
Always write meaningful alternative text (`alt`) so that:
- **Screen readers** can help visually impaired users understand the image.  
- If the image fails to load, users can still know what it was supposed to display.  

**Example of a bad `alt` text:**  
```html
<img src="image/img1.jpeg" alt="Image">
```
(Too vague—doesn't describe the image.)  

**Example of a good `alt` text:**  
```html
<img src="image/img1.jpeg" alt="A beautiful sunset over the mountains">
```
(This describes the image properly.)  

---

### ✅ 3. **Use CSS for Better Image Control**  
Instead of using `width="500px"` and `height="400px"` in HTML, it's better to use CSS:  

```css
img {
    width: 100%; /* Makes images responsive */
    max-width: 500px; /* Ensures it doesn’t get too large */
    height: auto; /* Keeps the aspect ratio */
}
```
This ensures images adjust properly on different screen sizes.  

---

## **🔹 Note:**  
- **Offline images** are stored locally and referenced using a relative file path.  
- Always use **proper `alt` text** for accessibility and fallback purposes.  
- Use **CSS for responsive images** instead of hardcoding width and height in HTML.  

💡 **Practice:** Try adding more images, change their sizes, and use CSS to style them! 🚀