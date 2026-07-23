# JavaScript BigInt

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-BigInt-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript BigInt stores integer values larger than normal numbers can safely handle.**

</div>

---

## Quick Summary

- BigInt is used for very large integers.
- Add `n` after an integer to create a BigInt.
- `BigInt()` can also create a BigInt.
- BigInt values cannot have decimals.
- BigInt and Number values cannot be mixed directly in arithmetic.

---

## Key Points

| Item | Simple Meaning |
| :--- | :--- |
| `123n` | BigInt literal with `n` suffix. |
| `BigInt()` | Creates a BigInt value. |
| `typeof` | Returns `"bigint"` for BigInt values. |
| `Number.MAX_SAFE_INTEGER` | Largest safe integer for normal numbers. |
| `Number.MIN_SAFE_INTEGER` | Smallest safe integer for normal numbers. |
| `Number()` | Converts BigInt to Number. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = 999999999999999n;
let y = BigInt("999999999999999");

console.log(x);
console.log(y);
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = BigInt(999999999999999);
let type = typeof x;

console.log(type);
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = 10n;
let y = 5;

let z = Number(x) + y;

console.log(z);
```
</details>

---

## Remember

- BigInt is only for integers.
- Normal JavaScript numbers are accurate up to 15 digits.
- BigInt supports arithmetic operators like `+`, `-`, `*`, `/`, `%`, and `**`.
- Large BigInts can lose precision when converted to Number.
- `Math` functions do not work with BigInt values.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
