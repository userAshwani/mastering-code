# JavaScript HTML DOM

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-HTML_DOM-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The HTML DOM represents a web page as a tree of nodes that JavaScript can inspect and modify.**

</div>

---

## Quick Summary

- The HTML DOM turns HTML elements into programmable JavaScript objects.
- The browser creates the DOM tree automatically when a page loads.
- JavaScript can modify content, attributes, and CSS styles via the DOM.
- JavaScript can react to HTML events using DOM methods and properties.
- The W3C DOM standard defines standard interfaces for accessing document nodes.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **DOM Tree** | Node structure representing elements, attributes, and text on a page. |
| **Document Node** | The root owner object for all elements in an HTML document. |
| **DOM Methods** | Functions used to find, add, or delete HTML elements. |
| **DOM Properties** | Values like innerHTML or style used to read or modify elements. |

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

- The DOM is created by the browser whenever an HTML document is loaded.
- document is the root object used to access any HTML element.
- innerHTML changes element text and nested HTML markup.
- DOM standards are defined by the W3C and WHATWG committees.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
