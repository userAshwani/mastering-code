# JavaScript HTML DOM Changing HTML

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-DOM_HTML-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript can dynamically change HTML content, attribute values, and dynamic elements in real time.**

</div>

---

## Quick Summary

- The innerHTML property changes the inner content of an HTML element.
- The attribute property updates values like src, href, alt, or title.
- document.write() writes directly to the HTML output stream during page loading.
- setAttribute() changes the value of any specified attribute on an element.
- Dynamic content updates take effect immediately on the user screen.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **innerHTML** | Property used to read or change element HTML content. |
| **setAttribute()** | Method used to set or update attribute values. |
| **attributeName** | Direct property access like element.src or element.href. |
| **document.write()** | Writes text directly to HTML output during page render. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.getElementById(id).innerHTML = new HTML
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<html>

<body>


<p id="p1">Hello World!</p>


<script>

document.getElementById("p1").innerHTML = "New text!";

</script>


</body>

</html>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<!DOCTYPE html>
<html>

<body>



<h1 id="id01">Old Heading</h1>



<script>

const element = document.getElementById("id01");
element.innerHTML = "New Heading";

</script>



</body>

</html>
```
</details>

---

## Remember

- Using document.write() after a page has loaded deletes all existing HTML.
- element.src changes image sources dynamically.
- element.attributeName works for standard HTML attributes.
- innerHTML parses HTML strings and updates the element tree.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
