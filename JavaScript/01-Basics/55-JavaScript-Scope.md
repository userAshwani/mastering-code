# JavaScript Scope

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Scope decides where variables can be accessed in JavaScript.**

</div>

---

## Quick Summary

- Scope controls variable visibility.
- JavaScript has block scope, function scope, and global scope.
- Variables declared inside a function are local to that function.
- Global variables can be accessed from anywhere.

---

## Key Points

| Scope Type | Meaning |
| :--- | :--- |
| Block Scope | Variables inside `{ }` can stay inside that block. |
| Function Scope | Variables inside a function belong to that function. |
| Global Scope | Variables outside functions are global. |
| Automatically Global | Assigning a value to an undeclared variable can create a global variable. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function myFunction() {
  let carName = "Volvo";
  return carName;
}
```
</details>

---

## Remember

- `let` and `const` have block scope.
- `var` has function scope.
- Local variables are created when a function starts.
- Local variables are deleted when the function completes.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
