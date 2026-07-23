# JavaScript Number Reference

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Number_Reference-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**A complete reference guide to JavaScript Number properties, static methods, and instance methods.**

</div>

---

## Quick Summary

- `Number` properties provide standard numeric constants and boundary values.
- Instance methods format or convert individual number values (e.g., `toFixed()`).
- Static `Number` methods perform checks and parsing on numbers (e.g., `Number.isInteger()`).
- Global methods like `parseInt()` are also accessible as static methods on `Number`.
- All JavaScript numbers share the same double-precision 64-bit float type.

---

## Key Points

| Category | Member | Description |
| :--- | :--- | :--- |
| **Properties** | `MAX_VALUE`, `MIN_VALUE`, `NaN`, `EPSILON` | Numeric limits, constants, and boundary values |
| **Instance Methods** | `toFixed()`, `toPrecision()`, `toString()` | Formats or converts a number value into a string |
| **Static Methods** | `Number.isInteger()`, `Number.isNaN()` | Checks if a value satisfies numeric conditions |
| **Parsing Methods** | `Number.parseInt()`, `Number.parseFloat()` | Parses text into numeric integers or floats |
| **Conversion** | `valueOf()`, `toLocaleString()` | Returns primitive value or localized string |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Instance Methods (called on number values)
let num = 12.3456;
console.log(num.toFixed(2));        // "12.35"
console.log(num.toPrecision(3));    // "12.3"
console.log(num.toString());        // "12.3456"

// Static Methods (called on Number object)
console.log(Number.isInteger(10));   // true
console.log(Number.isInteger(10.5)); // false
console.log(Number.isNaN(NaN));      // true

// Parsing Methods
console.log(Number.parseInt("42px"));  // 42
console.log(Number.parseFloat("3.14"));// 3.14
```
</details>

---

## Remember

- Instance methods must be called on a specific number value or variable.
- Static methods must be called using the `Number.` prefix (e.g. `Number.isInteger()`).
- Number properties (like `MAX_VALUE`) are static constants and cannot be called on variables.
- `Number.isNaN()` is stricter than global `isNaN()` as it does not coerce non-numbers.
- Formatting methods like `toFixed()` return a **string**, not a number.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
