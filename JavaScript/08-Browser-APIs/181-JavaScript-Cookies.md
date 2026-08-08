# JavaScript Cookies

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Cookies-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Cookies are small text data stored in the user browser to remember user preferences across visits.**

</div>

---

## Quick Summary

- Cookies store key-value pairs as text strings on the visitor computer.
- document.cookie is used to create, read, and delete cookies.
- Cookies can specify an expiration date using expires= or max-age=.
- By default, cookies belong to the current page path.
- Cookies can be deleted by setting an expiration date in the past.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Create Cookie** | document.cookie = "username=John; expires=Date; path=/"; |
| **Read Cookie** | document.cookie returns string of all semicolon-separated cookies. |
| **Delete Cookie** | Set cookie expires parameter to past date. |
| **path Attribute** | Defines path boundary where cookie is accessible. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
username = John Doe
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.cookie = "username=John Doe";
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.cookie = "username=John Doe; expires=Thu, 18 Dec 2013 12:00:00 UTC";
```
</details>

---

## Remember

- document.cookie does not overwrite all cookies; it appends or updates key-value pairs.
- Setting expires in the past immediately deletes a cookie.
- Cookies are automatically sent to the server on subsequent HTTP requests.
- Use encodeURIComponent() to handle special characters in cookie values.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
