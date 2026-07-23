# JavaScript Break and Continue

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Break_%26_Continue-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**`break` exits a loop early, and `continue` skips the current iteration and moves to the next.**

</div>

---

## Quick Summary

- `break` jumps out of a loop immediately and stops it.
- `continue` skips the rest of the current iteration and continues to the next one.
- Both work inside `for`, `while`, and `do/while` loops.
- A **label** lets you target an outer loop with `break` or `continue`.
- Labels are placed before the loop and referenced by name.

---

## Key Points

| Statement | What It Does | Works In |
| :--- | :--- | :--- |
| `break` | Exits the loop completely | `for`, `while`, `do/while`, `switch` |
| `continue` | Skips current iteration, continues loop | `for`, `while`, `do/while` |
| `label:` | Names a block or loop for targeting | Any loop or block |
| `break label` | Breaks out of the labeled outer loop | Nested loops |
| `continue label` | Continues the labeled outer loop | Nested loops |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// break — stops the loop when i equals 3
for (let i = 0; i < 5; i++) {
  if (i === 3) break;
  console.log(i);
}
// Output: 0, 1, 2

// continue — skips i equal to 3
for (let i = 0; i < 5; i++) {
  if (i === 3) continue;
  console.log(i);
}
// Output: 0, 1, 2, 4

// label with break — exits the outer loop
outer: for (let i = 0; i < 3; i++) {
  for (let j = 0; j < 3; j++) {
    if (j === 1) break outer;
    console.log(i, j);
  }
}
// Output: 0 0
```
</details>

---

## Remember

- `break` fully stops the loop; execution continues after the loop block.
- `continue` only skips the **current** iteration, not the whole loop.
- Labels must be placed **directly before** the loop they target.
- `break` can also be used inside a `switch` statement to exit it.
- Avoid overusing labels — they can make code harder to read.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
