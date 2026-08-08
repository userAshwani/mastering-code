# JavaScript Asynchronous

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Asynchronous-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Asynchronous JavaScript allows tasks to run in the background without blocking the main thread execution.**

</div>

---

## Quick Summary

- JavaScript is single-threaded, executing one operation at a time.
- Asynchronous operations allow code to continue while waiting for slow tasks to complete.
- setTimeout() schedules a callback to run after a specified delay in milliseconds.
- Asynchronous patterns include callbacks, Promises, async/await, and event loops.
- Prevents blocking UI rendering during long-running operations like network calls.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Synchronous** | Code executes line by line blocking until each completes. |
| **Asynchronous** | Delayed or background operations without blocking execution. |
| **setTimeout(fn, ms)** | Runs callback after specified millisecond delay. |
| **Event Loop** | Mechanism that processes async callbacks from the queue. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Example illustrating JavaScript Asynchronous
console.log("JavaScript Asynchronous demo");
```
</details>

---

## Remember

- JavaScript does not pause at asynchronous operations — it moves to the next line.
- Callbacks run after async tasks complete, not at the point they were defined.
- Promises and async/await make asynchronous code more readable and manageable.
- Never block the main JavaScript thread with long synchronous operations.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
