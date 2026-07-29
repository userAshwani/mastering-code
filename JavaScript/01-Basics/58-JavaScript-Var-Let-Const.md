# JavaScript var let and const

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**`var`, `let`, and `const` are used to declare variables with different rules.**

</div>

---

## Quick Summary

- `var` is the older way to declare variables.
- `let` is used for values that can change.
- `const` is used for values that should not be reassigned.
- `let` and `const` have block scope.

---

## Key Points

| Keyword | Main Rule |
| :--- | :--- |
| `var` | Function scoped and can be redeclared. |
| `let` | Block scoped and can be reassigned. |
| `const` | Block scoped and cannot be reassigned. |
| Block Scope | Applies to `let` and `const`. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = 10;
const y = 20;
var z = 30;
```
</details>

---

## Remember

- Use `const` when the value should not change.
- Use `let` when the value can change.
- Avoid redeclaring variables.
- `var` behaves differently from `let` and `const`.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
