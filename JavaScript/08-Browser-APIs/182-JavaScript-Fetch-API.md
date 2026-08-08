# JavaScript Fetch API

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Fetch_API-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The Fetch API provides a modern Promise-based interface for making asynchronous network requests.**

</div>

---

## Quick Summary

- fetch() initiates an asynchronous HTTP request to a URL and returns a Promise.
- The response object requires calling methods like .json() or .text() to parse body data.
- .then() handles successful asynchronous HTTP responses.
- .catch() handles network failures and rejected requests.
- async/await simplifies writing fetch request pipelines.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **fetch(url)** | Sends HTTP GET request returning a Promise. |
| **response.json()** | Parses JSON response body asynchronously. |
| **response.text()** | Parses raw text response body asynchronously. |
| **response.ok** | Boolean indicating if status code is in 200-299 range. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Fetch a file

fetch(file)

  .then(function(response) {

      return response.text();

  })

  .then(function(data) {

    myDisplayer(data);

  });
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Fetch a file

fetch(file)

  .then(response => response.text())

  .then(data => myDisplayer(data));
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Async function to fetch a file

async function loadText(file) {

  const response = await fetch(file);

  myDisplayer(await response.text());

}
```
</details>

---

## Remember

- fetch() Promise only rejects on network failure, not on HTTP 404 or 500 errors.
- Check response.ok to verify HTTP status success.
- response.json() returns a Promise that resolves with parsed JSON data.
- Pass configuration objects to send POST requests with headers and payload body.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
