# JavaScript Events

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Events-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript events allow web pages to execute code when user actions or browser events occur.**

</div>

---

## Quick Summary

- An event is a signal that something has happened on a web page.
- Events can be triggered by user interactions like clicks, keypresses, or mouse movements.
- HTML event attributes like onclick execute inline JavaScript code directly.
- Event handler functions run automatically when the associated event fires.
- Common events include onclick, onload, onchange, onmouseover, and onkeydown.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **onclick** | Fires when the user clicks on an HTML element. |
| **onchange** | Fires when the value of an input element changes. |
| **onload** | Fires when the browser finishes loading a page or image. |
| **onmouseover** | Fires when the mouse pointer moves over an element. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<element
event='some JavaScript'>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<element
event="some JavaScript">
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>
```
</details>

---

## Remember

- Events connect user interaction with JavaScript code execution.
- HTML event names in attributes start with the "on" prefix (e.g., onclick).
- Event handlers can receive an event object detailing the action.
- Keeping event handlers in JavaScript files is preferred over inline attributes.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
