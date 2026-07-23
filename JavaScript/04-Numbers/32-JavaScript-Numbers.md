# JavaScript Numbers

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Numbers-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript has only one type of number, stored as 64-bit floating-point numbers.**

</div>

---

## Quick Summary

- All JavaScript numbers are stored as 64-bit floating-point values.
- Integers are accurate up to 15 digits without exponential notation.
- Adding a number and a string results in string concatenation (`"10" + 20 = "1020"`).
- `NaN` is a reserved keyword indicating a value is Not-a-Number.
- `Infinity` is returned when a number exceeds the upper calculation limit.

---

## Key Points

| Concept | Description | Example |
| :--- | :--- | :--- |
| **Float Standard** | Stored as 64-bit floating point | `let x = 3.14;` |
| **String Concatenation** | `+` operator joins string and number operands | `"20" + 10` → `"2010"` |
| **Numeric Conversion** | `-`, `*`, `/` convert numeric strings to numbers | `"100" / "10"` → `10` |
| **NaN Check** | `isNaN()` checks if a value is not a number | `isNaN("Hello")` → `true` |
| **Infinity** | Result of dividing by zero or exceeding maximum limit | `2 / 0` → `Infinity` |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Integer and Decimal numbers
let x = 3.14; // A number with decimals
let y = 3;    // A number without decimals

// Extra precision issue with floats
let z = 0.1 + 0.2;
console.log(z); // 0.30000000000000004

// Adding numbers and strings
let a = 10;
let b = "20";
console.log(a + b); // "1020"

// Other math operators convert numeric strings
console.log("100" / "10"); // 10
console.log("100" - "50"); // 50

// NaN (Not a Number) and Infinity
let result = 100 / "Apple";
console.log(result);         // NaN
console.log(isNaN(result));  // true
console.log(typeof Infinity);// "number"
```
</details>

---

## Remember

- Floating-point arithmetic is not always 100% accurate; multiply and divide to solve precision.
- JavaScript executes addition and concatenation from left to right.
- `typeof NaN` and `typeof Infinity` both return `"number"`.
- Dividing by zero (`0`) generates `Infinity` in JavaScript.
- Avoid creating Number objects with `new Number()` because they slow down execution speed.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
