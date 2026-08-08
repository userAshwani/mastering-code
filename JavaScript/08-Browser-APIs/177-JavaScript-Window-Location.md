# JavaScript Window Location

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Window_Location-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The window.location object gets the current page address (URL) and can redirect the browser to a new page.**

</div>

---

## Quick Summary

- location.href returns the full URL address of the current web page.
- location.hostname returns the domain name of the web host.
- location.pathname returns the path and filename of the current page.
- location.protocol returns the web protocol used (http: or https:).
- location.assign() loads a new document into the browser window.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **location.href** | Returns full URL of current page or sets URL to redirect. |
| **location.hostname** | Returns domain host name. |
| **location.pathname** | Returns path and filename of URL. |
| **location.assign()** | Loads a new document in the browser. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.getElementById("demo").innerHTML =
"Page location is " + window.location.href;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.getElementById("demo").innerHTML =
"Page hostname is " + window.location.hostname;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.getElementById("demo").innerHTML =
"Page path is " + window.location.pathname;
```
</details>

---

## Remember

- Setting location.href = "URL" redirects the browser to that page.
- location.assign() adds the new URL to browser history.
- location.replace() replaces current document without saving history.
- window.location can be accessed directly as location.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
