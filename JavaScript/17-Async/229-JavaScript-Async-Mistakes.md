# JavaScript Async Mistakes

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Async_Mistakes-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Common async JavaScript mistakes include missing await, unhandled rejections, and sequential bottlenecks.**

</div>

---

## Quick Summary

- Forgetting await causes code to receive a Promise object instead of resolved value.
- Missing .catch() or try-catch leads to unhandled Promise rejection warnings.
- Using sequential await for independent tasks wastes time versus using Promise.all().
- Returning inside forEach() does not work for async operations — use for...of loop.
- Mixing callbacks and Promises without care creates confusing execution order.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Missing await** | Variable receives Promise, not its resolved value. |
| **Unhandled Rejection** | No .catch() or try-catch on rejected Promise. |
| **forEach + async** | forEach ignores returned Promises — use for...of. |
| **Sequential bottleneck** | Awaiting independent tasks one-by-one wastes time. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const response = fetch("demo.txt");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const response = await fetch("demo.txt");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function load() {

  let response = await fetch("demo.txt");

}
```
</details>

---

## Remember

- Always use try-catch or .catch() to handle async errors gracefully.
- Use for...of or Promise.all() instead of forEach for async array processing.
- Parallel Promises with Promise.all() reduce total wait time for independent tasks.
- Test async code carefully — timing-related bugs can be intermittent and hard to trace.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
