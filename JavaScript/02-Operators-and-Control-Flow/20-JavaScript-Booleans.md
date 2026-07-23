# JavaScript Booleans

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Booleans-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript booleans can only have two values: `true` or `false`.**

</div>

---

## Quick Summary

- Booleans are primitive data types.
- Boolean values are `true` and `false`.
- `true` and `false` must be lowercase.
- Comparisons return boolean values.
- `Boolean()` checks if a value is true or false.

---

## Key Points

| Item | Simple Meaning |
| :--- | :--- |
| `true` | A true boolean value. |
| `false` | A false boolean value. |
| Comparison | Returns `true` or `false`. |
| Condition | Uses boolean logic to run code. |
| `Boolean()` | Converts a value to `true` or `false`. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = 5;

console.log(x == 8);
console.log(x != 8);
console.log(x > 8);
console.log(x < 8);
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
console.log(Boolean(10 > 9));
console.log(10 > 9);
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = 0;
console.log(Boolean(x));
```
</details>

---

## Remember

- Values like `100`, `"Hello"`, `[]`, and `{}` are true.
- Values like `0`, `""`, `undefined`, `null`, `NaN`, and `false` are false.
- Booleans are used in comparisons, conditions, and loops.
- Do not create Boolean objects with `new Boolean()`.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
