# JavaScript Window Screen

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Window_Screen-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The window.screen object contains information about the visitor monitor screen resolution and color depth.**

</div>

---

## Quick Summary

- screen.width returns the total width of the user screen in pixels.
- screen.height returns the total height of the user screen in pixels.
- screen.availWidth returns available screen width excluding interface features like taskbars.
- screen.availHeight returns available screen height excluding interface taskbars.
- screen.colorDepth returns the bit depth of the color palette used by the monitor.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **screen.width** | Total screen width in pixels. |
| **screen.height** | Total screen height in pixels. |
| **screen.availWidth** | Available screen width excluding OS taskbars. |
| **screen.availHeight** | Available screen height excluding OS taskbars. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.getElementById("demo").innerHTML =
"Screen Width: " + screen.width;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.getElementById("demo").innerHTML =
"Screen Height: " + screen.height;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.getElementById("demo").innerHTML =
"Available Screen Width: " + screen.availWidth;
```
</details>

---

## Remember

- window.screen object can be written without the window. prefix.
- screen.availHeight is smaller than screen.height if an OS taskbar is present.
- screen.colorDepth indicates screen color capabilities (e.g., 24-bit).
- screen properties read monitor specs, not browser window size.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
