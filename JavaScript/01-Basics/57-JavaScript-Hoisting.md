# JavaScript Hoisting

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Hoisting means declarations are moved to the top of their scope before code runs.**

</div>

---

## Quick Summary

- JavaScript hoists declarations.
- `var` declarations are hoisted.
- `let` and `const` are hoisted but not initialized.
- Declarations are hoisted, initializations are not.

---

## Key Points

| Item | Hoisting Behavior |
| :--- | :--- |
| `var` | Can be used before declaration, value is `undefined`. |
| `let` | Cannot be used before declaration. |
| `const` | Cannot be used before declaration. |
| Initialization | Stays where it is written. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
x = 5;
var x;
```
</details>

---

## Remember

- Always declare variables before use.
- `let` and `const` must be declared before use.
- Hoisting can make `var` confusing.
- Initial values are not moved to the top.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
