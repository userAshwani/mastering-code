# JavaScript HTML DOM Methods

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-DOM_Methods-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**DOM methods are actions performed on HTML elements, while DOM properties are values you can set or get.**

</div>

---

## Quick Summary

- DOM methods are functions used to select or manipulate HTML elements.
- DOM properties are values of HTML elements that can be retrieved or modified.
- getElementById() finds an element using its unique id attribute.
- innerHTML is a DOM property used to get or replace element content.
- Methods and properties form the programming interface of the HTML DOM.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **getElementById()** | Method to find an HTML element by its ID. |
| **innerHTML** | Property to read or change the HTML content of an element. |
| **getElementsByTagName()** | Method to find HTML elements by tag name. |
| **getElementsByClassName()** | Method to find HTML elements by class name. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<html>

<body>


<p id="demo"></p>


<script>

// Access a paragraph Element

const myPara = document.getElementById("demo");



// Change the content of the Element

myPara.innerHTML = "Hello World!";

</script>


</body>

</html>
```
</details>

---

## Remember

- Methods perform actions on elements, whereas properties set or get element values.
- getElementById() returns a single element object.
- innerHTML can inject new HTML tags directly into an existing element.
- Always verify an element exists before calling methods on it.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
