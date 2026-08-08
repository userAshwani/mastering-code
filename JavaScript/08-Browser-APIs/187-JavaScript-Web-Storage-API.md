# JavaScript Web Storage API

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Web_Storage_API-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The Web Storage API allows web applications to store key-value data locally inside the user browser.**

</div>

---

## Quick Summary

- window.localStorage stores data with no expiration date across browser sessions.
- window.sessionStorage stores data for one browser tab session (cleared on close).
- setItem(key, value) saves a key-value data pair in storage.
- getItem(key) retrieves data associated with a specified storage key.
- removeItem(key) and clear() remove items from storage.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **localStorage** | Persistent local storage with no expiration time. |
| **sessionStorage** | Session storage valid until browser tab is closed. |
| **setItem(k, v)** | Saves string key-value pair into storage. |
| **getItem(k)** | Retrieves string value associated with key. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
localStorage.setItem("name", "John Doe");

localStorage.getItem("name");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
localStorage.setItem("name", "John Doe");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
localStorage.getItem("name");
```
</details>

---

## Remember

- Web Storage only stores strings — use JSON.stringify() to store objects/arrays.
- Use JSON.parse() when reading stored JSON objects back from storage.
- localStorage data persists even after restarting the computer.
- Storage limit is around 5MB per origin, much larger than cookies.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
