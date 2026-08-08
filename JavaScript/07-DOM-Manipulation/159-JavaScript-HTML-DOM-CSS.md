# JavaScript HTML DOM CSS

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-DOM_CSS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript can dynamically view and modify CSS inline styles and class names of HTML elements.**

</div>

---

## Quick Summary

- The style property allows changing CSS inline styles of HTML elements directly.
- CSS property names in JavaScript use camelCase format (e.g., backgroundColor).
- className reads or modifies the entire class attribute of an element.
- classList provides methods like add(), remove(), and toggle() for managing classes.
- Dynamic style changes enable interactive UI effects and themes.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **element.style.property** | Sets inline CSS properties directly on an element. |
| **camelCase Format** | Converts hyphenated CSS (background-color) to backgroundColor. |
| **classList.add()** | Adds one or more class names to an element. |
| **classList.toggle()** | Toggles a class name on or off on an element. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.getElementById(id).style.property= new style
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<html>

<body>


<p id="p2">Hello World!</p>



<script>

document.getElementById("p2").style.color = "blue";

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

<h1 id="id1">My Heading 1</h1>


<button type="button" 
onclick="document.getElementById('id1').style.color = 'red'">

Click Me!</button>

</body>
</html>
```
</details>

---

## Remember

- CSS property hyphenated names become camelCase in JavaScript style objects.
- Setting element.style applies inline styles overriding stylesheet defaults.
- classList.toggle() is ideal for dark mode switches or accordion panels.
- Assigning an empty string to element.style.property resets the inline style.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
