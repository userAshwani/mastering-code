# JavaScript Async Event Loop

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Event_Loop-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The JavaScript event loop processes asynchronous callbacks from the queue after the call stack is empty.**

</div>

---

## Quick Summary

- The call stack runs synchronous code one operation at a time.
- Web APIs handle async tasks like setTimeout() outside the main call stack.
- Completed async callbacks are placed in the task queue (macro-task queue).
- The event loop moves callbacks from the queue to the call stack when stack is empty.
- Microtask queue (Promises) runs before the macrotask queue on each cycle.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Call Stack** | Executes synchronous function calls in last-in-first-out order. |
| **Task Queue** | Holds callbacks from setTimeout, setInterval for later execution. |
| **Microtask Queue** | Holds Promise callbacks; runs before task queue each cycle. |
| **Event Loop** | Moves tasks from queue to empty call stack continuously. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function step1() {

  myDisplayer("Step 1");

}

function step2() {

  myDisplayer("Step 2");

}


step1();

step2();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
Step 1

Step 2
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function step1() {

  myDisplayer("Step 1");

}

function step2() {

  myDisplayer("Step 2");

}


step2();

step1();
```
</details>

---

## Remember

- Promise .then() callbacks enter the microtask queue — higher priority than setTimeout.
- The event loop only picks tasks when the call stack is completely empty.
- Blocking the call stack with long synchronous code freezes async task processing.
- Understanding the event loop is essential for debugging async JavaScript behavior.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
