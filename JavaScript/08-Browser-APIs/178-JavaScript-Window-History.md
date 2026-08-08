# JavaScript Window History

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Window_History-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The window.history object contains the browser history and allows navigating backward or forward.**

</div>

---

## Quick Summary

- history.back() loads the previous URL in the browser history list (same as back button).
- history.forward() loads the next URL in the browser history list (same as forward button).
- history.go() navigates to a specific page relative to current position.
- history.length returns the number of URLs in the history list.
- Access is restricted due to privacy; scripts cannot read actual URL strings in history.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **history.back()** | Navigates back one page in history. |
| **history.forward()** | Navigates forward one page in history. |
| **history.go(-2)** | Navigates back two pages in history. |
| **history.length** | Returns total entries in browser session history. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let length = window.history.length;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let length = history.length;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.getElementById("demo").innerHTML = history.length;
```
</details>

---

## Remember

- Scripts cannot view actual URLs in history due to security and privacy rules.
- history.back() is equivalent to clicking the browser back button.
- history.forward() requires prior backward navigation to work.
- history.go(0) reloads the current page.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
