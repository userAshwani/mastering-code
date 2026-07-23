# JavaScript Where To

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Where_To-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript can be placed inside HTML pages or loaded from external files.**

</div>

---

## Quick Summary

- JavaScript code is placed inside `<script>` tags.
- Scripts can be placed in the `<head>` or `<body>`.
- External scripts are stored in separate `.js` files.
- External files help reuse the same code on many pages.

---

## Key Points

| Method | Simple Meaning |
| :--- | :--- |
| Internal script | JavaScript written inside an HTML file. |
| External script | JavaScript stored in a separate file. |
| `<head>` script | Runs before or while the page is loading. |
| `<body>` script | Often runs after page elements exist. |
| External file | Linked with the `src` attribute. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```html
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```html
<script src="myScript.js"></script>
```
</details>

---

## Remember

- Use `<script>` to add JavaScript to HTML.
- External scripts use the `src` attribute.
- External scripts cannot contain `<script>` tags.
- One external script can be reused by many pages.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
