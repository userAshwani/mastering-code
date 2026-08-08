# JavaScript Async Await Deep Dive

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Async_Await_Deep-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**async/await provides syntactic sugar over Promises enabling cleaner sequential asynchronous code flow.**

</div>

---

## Quick Summary

- async functions are declared using the async keyword before function definition.
- await suspends execution of an async function until the awaited Promise settles.
- Errors in async functions are caught using try-catch or .catch() on the returned Promise.
- await can only be used inside functions marked as async.
- Top-level await is supported inside ES modules without an async function wrapper.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **async Declaration** | async function name() {} returns a Promise. |
| **await Pausing** | Pauses inside async function until Promise resolves. |
| **try-catch** | Catches errors from awaited rejected Promises. |
| **Top-level await** | Usable at module top level without async wrapper. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create an async function

async function hello() {

  return "Hello World!";

}


// Call the async function

hello().then(function(value) {

  myDisplayer(value);

});
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create an async function

async function getData() {

  let response = await fetch("fetch.txt");

  let text = await response.text();

  myDisplayer(text);

}


// Call the async function

getData();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
myDisplayer("Start");



// Create an async function

async function getData() {

  await fetch("fetch.txt");

  myDisplayer("Done");

}



// Call the async function

getData();



myDisplayer("Continue");
```
</details>

---

## Remember

- async/await makes asynchronous code easier to read like sequential steps.
- await does not block the overall browser thread — only the async function.
- Parallel async operations should use Promise.all([...]) with await.
- An unhandled rejected Promise from async functions triggers an unhandled rejection warning.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
