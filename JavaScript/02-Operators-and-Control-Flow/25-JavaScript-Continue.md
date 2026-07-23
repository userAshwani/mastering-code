# JavaScript Continue

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Continue-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The `continue` statement skips one iteration of a loop and jumps to the next.**

</div>

---

## Quick Summary

- `continue` skips the **current** iteration and moves to the next one.
- It does **not** stop the loop — the loop keeps running.
- Works inside `for`, `while`, and `do/while` loops.
- You can use a **label** with `continue` to target an outer loop.
- It is the opposite of `break` — `break` exits, `continue` skips.

---

## Key Points

| Feature | Detail |
| :--- | :--- |
| **Skips** | Only the current iteration |
| **Loop continues** | Yes — remaining iterations still run |
| **Works in** | `for`, `while`, `do/while` |
| **With label** | Skips to next iteration of the labeled outer loop |
| **Does NOT exit** | The loop is not stopped |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// continue in a for loop — skips value 3
for (let i = 0; i < 6; i++) {
  if (i === 3) continue;
  console.log(i);
}
// Output: 0, 1, 2, 4, 5

// continue in a while loop — skips value 3
let i = 0;
while (i < 6) {
  i++;
  if (i === 3) continue;
  console.log(i);
}
// Output: 1, 2, 4, 5, 6

// continue with a label — skips to outer loop
outer: for (let i = 0; i < 3; i++) {
  for (let j = 0; j < 3; j++) {
    if (j === 1) continue outer;
    console.log(i, j);
  }
}
// Output: 0 0, 1 0, 2 0
```
</details>

---

## Remember

- `continue` skips **one** iteration, not the whole loop.
- The loop condition is still checked after `continue` runs.
- In a `while` loop, always update your counter **before** `continue` to avoid an infinite loop.
- A labeled `continue` skips to the next iteration of the **named outer loop**.
- `continue` cannot be used inside a `switch` statement to skip a loop iteration directly.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
