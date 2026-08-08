# JavaScript Async Fetch

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Async_Fetch-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The Fetch API combined with async/await provides a clean pattern for making asynchronous HTTP requests.**

</div>

---

## Quick Summary

- fetch() returns a Promise that resolves to a Response object.
- response.json() parses JSON body and also returns a Promise.
- async/await with fetch() simplifies sequential network request code.
- Always check response.ok to detect HTTP error status codes.
- try-catch wraps await fetch() to handle network failures gracefully.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **await fetch(url)** | Fetches URL and waits for response headers to arrive. |
| **await response.json()** | Waits for response body to be fully parsed as JSON. |
| **response.ok** | Boolean true if HTTP status code is 200-299 range. |
| **try-catch** | Catches network errors and rejected fetch Promises. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Async function to download a file

async function loadText(file) {

  const response = await fetch(file);

  myDisplayer(await response.text());

}



// Call the async function

loadText("demo.txt");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<p>The Fetch API interface allows web browser to make HTTP requests to web servers.</p>
<p>If you use the XMLHttpRequest Object, Fetch can do the same in a simpler way.</p>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Async function to download a file

async function loadText(file) {

  const response = await fetch(file);

  myDisplayer(response);

}
```
</details>

---

## Remember

- fetch() does not reject on HTTP errors like 404 or 500 — only on network failure.
- Always await both fetch() and response.json() sequentially.
- Pass RequestInit options object to fetch() for POST with headers and body.
- AbortController can cancel an in-progress fetch() request.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
