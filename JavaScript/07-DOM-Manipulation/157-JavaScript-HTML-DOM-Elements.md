# JavaScript HTML DOM Elements

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-DOM_Elements-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript provides multiple DOM methods to find, add, delete, and replace HTML elements on a page.**

</div>

---

## Quick Summary

- Elements can be found by ID, tag name, class name, CSS selectors, or HTML object collections.
- querySelector() returns the first element matching a specified CSS selector.
- querySelectorAll() returns all elements matching a specified CSS selector.
- createElement() and appendChild() create and add new elements to the DOM.
- removeChild() removes an existing element node from the document.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **querySelector()** | Finds the first element matching a CSS selector. |
| **querySelectorAll()** | Finds all elements matching a CSS selector as a NodeList. |
| **createElement()** | Creates a new HTML element node. |
| **appendChild()** | Appends a new child node to an existing element. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const element = document.getElementById("intro");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const element = document.getElementsByTagName("p");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const x = document.getElementById("main");

const y = x.getElementsByTagName("p");
```
</details>

---

## Remember

- querySelectorAll() returns a non-live NodeList of matching elements.
- createElement() creates an element in memory before it is appended to the DOM.
- removeChild() requires a reference to the parent element.
- CSS selectors can target elements by ID, class, type, or attribute.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
