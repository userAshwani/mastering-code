# JavaScript Number Properties

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Number_Properties-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Number properties provide numeric constants and limits belonging to the JavaScript Number object.**

</div>

---

## Quick Summary

- Number properties are constants defined on the wrapper object `Number`.
- `MAX_VALUE` and `MIN_VALUE` represent numeric limits in JavaScript.
- `MAX_SAFE_INTEGER` and `MIN_SAFE_INTEGER` define limits for safe integer math.
- `POSITIVE_INFINITY` and `NEGATIVE_INFINITY` represent overflow values.
- Number properties must be accessed via `Number.PROPERTY`, not variable instances.

---

## Key Points

| Property | Value / Description | Example |
| :--- | :--- | :--- |
| `Number.EPSILON` | Smallest interval between 1 and float above 1 | `Number.EPSILON` |
| `Number.MAX_VALUE` | Largest possible number (~1.79e+308) | `Number.MAX_VALUE` |
| `Number.MIN_VALUE` | Smallest possible positive number (~5e-324) | `Number.MIN_VALUE` |
| `Number.MAX_SAFE_INTEGER` | Maximum safe integer (`2^53 - 1`) | `Number.MAX_SAFE_INTEGER` |
| `Number.MIN_SAFE_INTEGER` | Minimum safe integer (`-(2^53 - 1)`) | `Number.MIN_SAFE_INTEGER` |
| `Number.NaN` | Not-a-Number value | `Number.NaN` |
| `Number.POSITIVE_INFINITY` | Overflow infinity value | `Number.POSITIVE_INFINITY` |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Accessing Number Constants
console.log(Number.MAX_VALUE);         // 1.7976931348623157e+308
console.log(Number.MIN_VALUE);         // 5e-324
console.log(Number.MAX_SAFE_INTEGER);  // 9007199254740991
console.log(Number.MIN_SAFE_INTEGER);  // -9007199254740991

// Overflow values
console.log(Number.POSITIVE_INFINITY); // Infinity
console.log(Number.NEGATIVE_INFINITY); // -Infinity
console.log(Number.NaN);               // NaN

// Accessing property on a variable returns undefined
let x = 6;
console.log(x.MAX_VALUE); // undefined
```
</details>

---

## Remember

- Number properties belong exclusively to the `Number` object wrapper.
- Using `myVariable.MAX_VALUE` returns `undefined` instead of the value.
- Any calculation producing a value larger than `MAX_VALUE` returns `Infinity`.
- Safe integers can be accurately represented and compared in JavaScript.
- `Number.EPSILON` is useful when testing floating-point equality.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
