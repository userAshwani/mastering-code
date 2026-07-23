# JavaScript `const`

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-const-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**`const` declares values that cannot be reassigned.**

</div>

---

## Quick Summary

- `const` was introduced in ES6.
- `const` variables must be assigned when declared.
- `const` variables cannot be reassigned.
- `const` variables have block scope.
- Constant arrays and objects can still have their contents changed.

---

## Key Points

| Rule | Simple Meaning |
| :--- | :--- |
| Must assign | `const` needs a value immediately. |
| No reassignment | The variable cannot be assigned again. |
| Block scope | Works only inside its block. |
| Arrays | Items can change, but the array cannot be reassigned. |
| Objects | Properties can change, but the object cannot be reassigned. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const PI = 3.14159265359;

console.log(PI);
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const cars = ["Saab", "Volvo", "BMW"];

cars[0] = "Toyota";
cars.push("Audi");

console.log(cars);
```
</details>

---

## Remember

- Use `const` when a value should not be reassigned.
- `const` must be initialized.
- `const` has block scope.
- Object and array contents can still change.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
