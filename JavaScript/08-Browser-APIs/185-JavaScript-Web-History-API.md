# JavaScript Web History API

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Web_History_API-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The Web History API allows navigating and updating browser URL history without full page reloads.**

</div>

---

## Quick Summary

- window.history provides methods to navigate browser session history.
- history.back() and history.forward() navigate backward and forward in history.
- history.pushState() adds a new state entry to browser history without reloading.
- history.replaceState() modifies the current history entry without creating a new item.
- popstate event fires when navigating between history states.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **pushState()** | Adds state entry to history stack and updates URL string. |
| **replaceState()** | Replaces current state entry on history stack. |
| **popstate Event** | Fires when user navigates using back/forward buttons. |
| **history.state** | Property returning current state object data. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<button onclick="myFunction()">Go Back</button>


<script>

function myFunction() {

  window.history.back();

  }

</script>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<button onclick="myFunction()">Go Back 2 Pages</button>

 
<script>

function myFunction() {

  window.history.go(-2);

 }

</script>
```
</details>

---

## Remember

- pushState() changes the URL address bar without reloading the web page.
- Essential for Single Page Application (SPA) routing.
- pushState() parameters: (stateObject, title, url).
- The popstate event fires on window when back or forward buttons are clicked.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
