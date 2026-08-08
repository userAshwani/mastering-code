# JavaScript Window Navigator

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Window_Navigator-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The window.navigator object contains information about the visitor browser and environment.**

</div>

---

## Quick Summary

- navigator.cookieEnabled returns true if cookies are enabled in the browser.
- navigator.language returns the language version of the browser.
- navigator.onLine returns true if the browser is connected to the internet.
- navigator.userAgent returns the user-agent string sent to the server.
- navigator.platform returns the operating system platform on which the browser is running.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **navigator.cookieEnabled** | Boolean indicating if cookies are enabled. |
| **navigator.language** | Browser primary language string (e.g., "en-US"). |
| **navigator.onLine** | Boolean indicating if browser has network connection. |
| **navigator.userAgent** | User-agent header string sent by browser. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<p id="demo"></p>



<script>

document.getElementById("demo").innerHTML =
"cookiesEnabled is " + navigator.cookieEnabled;

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

document.getElementById("demo").innerHTML = navigator.language;

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

document.getElementById("demo").innerHTML = navigator.onLine;

</script>
```
</details>

---

## Remember

- window.navigator can be accessed without the window. prefix.
- userAgent strings can be altered by users or spoofed by browsers.
- navigator.onLine detects network interface state, not actual internet connectivity.
- Use feature detection instead of userAgent checking when writing robust code.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
