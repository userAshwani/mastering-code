# JavaScript Timers

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Timers-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript timers run code after a delay or repeatedly at intervals.**

</div>

---

## Quick Summary

- `setTimeout()` runs a function after a delay.
- `setInterval()` runs a function repeatedly.
- `clearTimeout()` stops a timeout.
- `clearInterval()` stops an interval.

---

## Key Points

| Method | Simple Meaning |
| :--- | :--- |
| `setTimeout()` | Runs code once after waiting. |
| `clearTimeout()` | Stops a timeout before it runs. |
| `setInterval()` | Runs code again and again. |
| `clearInterval()` | Stops a running interval. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
setTimeout(myFunction, 3000);

function myFunction() {
  console.log("Hello");
}
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
setInterval(myTimer, 1000);

function myTimer() {
  const d = new Date();
  console.log(d.toLocaleTimeString());
}
```
</details>

---

## Remember

- Timer delay is written in milliseconds.
- `1000` milliseconds is 1 second.
- Use `clearTimeout()` to stop delayed code.
- Use `clearInterval()` to stop repeated code.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
