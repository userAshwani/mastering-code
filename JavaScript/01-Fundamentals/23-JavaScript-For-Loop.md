# JavaScript For Loop

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-For_Loop-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The `for` loop repeats a block of code a specific number of times.**

</div>

---

## Quick Summary

- A `for` loop runs code repeatedly as long as a condition is `true`.
- It has three parts: **initialization**, **condition**, and **increment**.
- It is the most common loop when you know how many times to iterate.
- You can loop through arrays and HTML elements using a `for` loop.
- The loop stops when the condition becomes `false`.

---

## Key Points

| Part | What It Does | Example |
| :--- | :--- | :--- |
| **Initialization** | Runs once before the loop starts | `let i = 0` |
| **Condition** | Checked before each iteration; stops when `false` | `i < 5` |
| **Increment** | Runs after each iteration | `i++` |
| **Loop Body** | The code that runs each time | `console.log(i)` |
| **`break`** | Exits the loop early | `if (i === 3) break;` |
| **`continue`** | Skips the current iteration | `if (i === 2) continue;` |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Basic for loop — prints 0 to 4
for (let i = 0; i < 5; i++) {
  console.log(i);
}
// Output: 0, 1, 2, 3, 4

// Loop through an array
const cars = ["BMW", "Volvo", "Saab"];
for (let i = 0; i < cars.length; i++) {
  console.log(cars[i]);
}
// Output: BMW, Volvo, Saab

// Using break — stops when i equals 3
for (let i = 0; i < 5; i++) {
  if (i === 3) break;
  console.log(i);
}
// Output: 0, 1, 2

// Using continue — skips i equal to 3
for (let i = 0; i < 5; i++) {
  if (i === 3) continue;
  console.log(i);
}
// Output: 0, 1, 2, 4
```
</details>

---

## Remember

- Initialization runs **only once** at the start of the loop.
- If the condition is **never false**, you get an infinite loop — always double-check it.
- `i++` is shorthand for `i = i + 1`; you can also use `i--` to count down.
- `break` exits the loop completely; `continue` skips to the next iteration.
- You can omit any of the three parts, but the semicolons `;` must stay.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
