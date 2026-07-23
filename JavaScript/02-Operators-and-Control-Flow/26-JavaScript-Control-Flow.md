# JavaScript Control Flow

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Control_Flow-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Control flow determines the execution order of statements in a JavaScript program.**

</div>

---

## Quick Summary

- Statements execute line by line from top to bottom by default.
- Conditionals alter control flow based on true or false conditions.
- Loops repeat code statements until a specific condition changes.
- Jump statements like `break` and `continue` redirect control flow.
- Functions pause current execution and resume after returning.

---

## Key Points

| Control Flow Structure | Purpose | Keywords |
| :--- | :--- | :--- |
| **Sequential** | Default line-by-line execution | Standard statements |
| **Conditional** | Executes code blocks on conditions | `if`, `else`, `switch` |
| **Iterative** | Repeats code execution in a loop | `for`, `while`, `do...while` |
| **Transfer** | Interrupts or redirects code execution | `break`, `continue`, `return` |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Sequential & Conditional control flow
let age = 18;

if (age >= 18) {
  console.log("Access granted.");
} else {
  console.log("Access denied.");
}

// Iterative control flow with transfer statement
for (let i = 1; i <= 5; i++) {
  if (i === 3) continue; // Skip iteration 3
  if (i === 5) break;    // Stop loop at 5
  console.log("Count:", i);
}
```
</details>

---

## Remember

- Without control flow statements, JavaScript code runs purely top-to-bottom.
- Use conditionals (`if`/`switch`) to make decision-based branches.
- Use loops (`for`/`while`) to repeat tasks efficiently.
- `break` exits a control structure immediately.
- `continue` skips straight to the next loop cycle.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
