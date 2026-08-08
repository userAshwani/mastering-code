# JavaScript HTML-First Features

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-HTML_First_Features-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**HTML-First features utilize modern HTML capabilities like native dialogs, popovers, and details elements.**

</div>

---

## Quick Summary

- Modern HTML offers built-in interactive features previously requiring JavaScript.
- <details> and <summary> create collapsible accordions natively without scripts.
- <dialog> element provides native modal windows with showModal() and close() methods.
- The popover attribute creates native popovers managed by the browser.
- Native features improve web performance and eliminate external widget dependencies.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **<details>** | Native expandable section without requiring JavaScript state. |
| **<dialog>** | Native modal dialog window with backdrop and focus trap. |
| **popover attribute** | Displays native popover elements on button clicks. |
| **showModal()** | Method to open a <dialog> element modally. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<details>

&nbsp;&nbsp;<summary>More information</summary>

&nbsp;&nbsp;<p>This text is hidden until the user opens it.</p>

</details>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<form action="/register" method="post">



<label for="username">Username:</label>

<input type="text" id="username" name="username" required minlength="3">



<label for="email">Email:</label>

<input type="email" id="email" name="email" required>



<button type="submit">Register</button>



</form>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<label for="birthday">Birthday:</label>

<input type="date" id="birthday" name="birthday">
```
</details>

---

## Remember

- <details open> creates open-by-default collapsible sections natively.
- <dialog> supports native keyboard ESC key closing out of the box.
- Using native features reduces JavaScript code size and improves performance.
- Browser support for modern HTML features eliminates heavy UI libraries.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
