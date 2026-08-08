# JavaScript Async and Await

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Async_Await-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**async and await keywords simplify working with Promises making asynchronous code look synchronous.**

</div>

---

## Quick Summary

- async function always returns a Promise automatically.
- await pauses execution inside an async function until a Promise resolves.
- await can only be used inside async function bodies.
- try-catch handles errors thrown in async functions cleanly.
- Multiple awaits can be chained sequentially inside a single async function.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **async function** | Declares function that returns a Promise automatically. |
| **await expression** | Pauses async function until Promise resolves. |
| **Error Handling** | Use try-catch inside async function to catch rejections. |
| **Return Value** | Returned value is wrapped in a resolved Promise automatically. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = 5;

let y = x * 2;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
myDisplayer("A");

myDisplayer("B");

myDisplayer("C");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function myFirst() {
  myDisplayer("Hello");
}

function 
  mySecond() {
  
  myDisplayer("Goodbye");
}

myFirst();
mySecond();
```
</details>

---

## Remember

- async/await is built on top of Promises — not a replacement but syntactic sugar.
- await does not block the main thread; only the async function pauses internally.
- An async function always returns a Promise even if you return a plain value.
- Use Promise.all() with await to run multiple async operations in parallel.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
