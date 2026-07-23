# JavaScript Logical Operators

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Logical_Operators-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript logical operators combine or change boolean expressions.**

</div>

---

## Quick Summary

- Logical operators work with boolean expressions.
- `&&` returns `true` when both expressions are true.
- `||` returns `true` when one or both expressions are true.
- `!` reverses a boolean result.
- `??` returns the right value when the left value is `null` or `undefined`.

---

## Key Points

| Operator | Name | Simple Meaning |
| :--- | :--- | :--- |
| `&&` | AND | True when both expressions are true. |
| `||` | OR | True when one or both expressions are true. |
| `!` | NOT | Reverses true and false. |
| `??` | Nullish coalescing | Uses the right value for `null` or `undefined`. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = 6;
let y = 3;
let z = (x < 10 && y > 1);

console.log(z);
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = 6;
let y = -3;
let z = (x > 0 || y > 0);

console.log(z);
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = (5 == 8);
let y = !(5 == 8);

console.log(x);
console.log(y);
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let name = null;
let text = "missing";
let result = name ?? text;

console.log(result);
```
</details>

---

## Remember

- Use comparison operators to check conditions.
- Use logical operators to combine conditions.
- `&&` needs both expressions to be true.
- `||` needs at least one expression to be true.
- `!` changes true to false and false to true.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
