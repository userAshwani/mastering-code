# JavaScript Page Load Events

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Load_Events-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Page load events fire during document parsing, resource loading, and window lifecycle transitions.**

</div>

---

## Quick Summary

- DOMContentLoaded fires when the HTML tree is parsed without waiting for images or stylesheets.
- window load fires when the entire page including images, stylesheets, and subframes has loaded.
- beforeunload fires right before the user navigates away or closes the tab.
- unload fires when the page resources are being unloaded from browser memory.
- Using DOMContentLoaded allows scripts to interact with the DOM faster than waiting for window load.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **DOMContentLoaded** | Fires when HTML document is fully parsed. |
| **load** | Fires when full page and all sub-resources finish loading. |
| **beforeunload** | Fires before leaving page; can prompt unsaved changes warnings. |
| **unload** | Fires as page is unmounted from window. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<p id="demo"></p>

<script>
// Add Event Listener to document
document.addEventListener("DOMContentLoaded", function () {
  document.getElementById("demo").innerHTML = "HTML is loaded!";
});
</script>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<p id="demo"></p>

<script>
// Add Event Listener to window
window.addEventListener("load", function () {
  document.getElementById("demo").innerHTML = "Page is fully loaded!";
});
</script>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<img id="myImg" src="image.jpg" width="120">

<p id="demo"></p>

<script>
const img = document.getElementById("myImg");

// Add Event Listener to img
img.addEventListener("load", function () {
  document.getElementById("demo").innerHTML = "Image loaded!";
});
</script>
```
</details>

---

## Remember

- DOMContentLoaded runs faster than window load because it ignores images.
- Attach DOMContentLoaded to document (document.addEventListener).
- Attach load and beforeunload to window (window.addEventListener).
- Modern browsers restrict custom messages in beforeunload dialogs.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
