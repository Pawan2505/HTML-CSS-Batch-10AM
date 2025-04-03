# **HTML Tables**
---

## **1. Introduction to Tables**
Tables in HTML are used to display data in a structured format with rows and columns. They are defined using the `<table>` element.

## **2. Basic Structure of a Table**
A table consists of several elements:
- `<table>` → Defines the table.
- `<caption>` → Provides a title for the table.
- `<thead>` → Contains the table header.
- `<tbody>` → Holds the main data.
- `<tfoot>` → Contains footer information.
- `<tr>` → Represents a row.
- `<th>` → Represents a header cell.
- `<td>` → Represents a data cell.

---

## **3. HTML Table Attributes**
### **a) Width & Height**
- You can define the table size using `width` and `height` attributes.
```html
<table width="900px" height="600px">
```

### **b) Border**
- Defines the thickness of table borders.
```html
<table border="1">
```

### **c) Cell Padding & Cell Spacing**
- `cellpadding` → Adds space inside each cell.
- `cellspacing` → Adds space between cells.
```html
<table cellpadding="10" cellspacing="5">
```

### **d) Aligning the Table**
- The `align` attribute centers the table.
```html
<table align="center">
```

---

## **4. Table Header (`<thead>`)**
The header row is usually styled differently from the body rows.
```html
<thead>
    <tr bgcolor="red">
        <th>S.No</th>
        <th>Name</th>
        <th>Email</th>
        <th>Course</th>
    </tr>
</thead>
```
- **`bgcolor="red"`** → Changes the background color of the header row.

---

## **5. Table Body (`<tbody>`)**
This section contains the main content.
```html
<tbody>
    <tr>
        <td>1</td>
        <td>Pawan</td>
        <td>pawan@gmail.com</td>
        <td>Full Stack</td>
    </tr>
</tbody>
```

---

## **6. Merging Cells using `rowspan` and `colspan`**
- **Rowspan (`rowspan="n"`)** → Merges a cell across multiple rows.
- **Colspan (`colspan="n"`)** → Merges a cell across multiple columns.

### **Example: Rowspan**
```html
<tr>
    <td rowspan="3">2</td> <!-- This cell spans 3 rows -->
    <td>Pawan</td>
    <td>pawan@gmail.com</td>
    <td>Full Stack</td>
</tr>
```

### **Example: Colspan**
```html
<tfoot>
    <tr>
        <td colspan="3" align="center">Duration</td> <!-- Spanning across 3 columns -->
        <td>1.5 year</td>
    </tr>
</tfoot>
```

---

## **7. Table Footer (`<tfoot>`)**
The `<tfoot>` section contains summary information.
```html
<tfoot>
    <tr>
        <td colspan="3" align="center">Duration</td>
        <td>1.5 years</td>
    </tr>
</tfoot>
```

---

## **8. Best Practices for Tables**
✅ Use `<thead>`, `<tbody>`, and `<tfoot>` for better structure.  
✅ Apply CSS for styling instead of inline attributes.  
✅ Avoid complex table structures for readability.  

---

## **9. Example: HTML Table**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Table</title>
</head>
<body>
    <table width="900px" height="600px" align="center" cellspacing="0" cellpadding="20" border="1">
        <caption>Student Table</caption>
        <thead>
            <tr bgcolor="red">
                <th>S.No</th>
                <th>Name</th>
                <th>Email</th>
                <th>Course</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Pawan</td>
                <td>pawan@gmail.com</td>
                <td>Full stack</td>
            </tr>
            <tr>
                <td rowspan="3">2</td>
                <td rowspan="2">Pawan</td>
                <td rowspan="2">pawan@gmail.com</td>
                <td>Full stack</td>
            </tr>
            <tr>
                <td>Full stack</td>
            </tr>
            <tr>
                <td>Pawan</td>
                <td>pawan@gmail.com</td>
                <td>Full stack</td>
            </tr>
            <tr>
                <td>5</td>
                <td>Pawan</td>
                <td>pawan@gmail.com</td>
                <td>Full stack</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="3" align="center">Duration</td>
                <td>1.5 year</td>
            </tr>
        </tfoot>
    </table>
</body>
</html>
```

---

### **10. Note:**
- **Tables** structure data into rows and columns.
- Use **`<thead>`, `<tbody>`, and `<tfoot>`** for better readability.
- **`rowspan` and `colspan`** help in merging cells.
- Tables can be styled using **CSS** for better design.

---
