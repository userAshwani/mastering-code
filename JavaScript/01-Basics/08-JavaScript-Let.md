# JavaScript `let`

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-let-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**`let` declares variables with block scope.**

</div>

---

## Quick Summary

- `let` was introduced in ES6.
- Variables declared with `let` have block scope.
- `let` variables can be reassigned.
- `let` cannot be redeclared in the same scope.
- `let` must be declared before use.

---

## Key Points

| Rule | Simple Meaning |
| :--- | :--- |
| Block scope | Only works inside the block where it is declared. |
| Reassignment | The value can change later. |
| No redeclaration | Same name cannot be declared again in the same scope. |
| Declare before use | Using it too early causes an error. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = 10;

{
  let x = 2;
  console.log(x);
}

console.log(x);
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let carName = "Volvo";
carName = "BMW";

console.log(carName);
```
</details>

---

## Remember

- `let` is block scoped.
- `let` can be reassigned.
- `let` cannot be redeclared in the same scope.
- Prefer `let` over `var` when a value must change.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
