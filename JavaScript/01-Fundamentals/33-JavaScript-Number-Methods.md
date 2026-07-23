# JavaScript Number Methods

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Number_Methods-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Number methods format, convert, and parse numeric values in JavaScript.**

</div>

---

## Quick Summary

- Number methods work on primitive numbers or number objects.
- Use `toFixed()` to format numbers with a fixed number of decimal places.
- Use `toPrecision()` to format numbers to a specified total length.
- `Number()`, `parseInt()`, and `parseFloat()` convert values into numbers.
- Global functions like `parseInt()` parse text and return numeric values.

---

## Key Points

| Method | Description | Example |
| :--- | :--- | :--- |
| `toString()` | Converts a number to a string | `(123).toString()` → `"123"` |
| `toFixed(decimals)` | Rounds a number to specified decimal places | `(9.656).toFixed(2)` → `"9.66"` |
| `toPrecision(length)` | Formats a number to a specific total length | `(9.656).toPrecision(2)` → `"9.7"` |
| `Number(value)` | Converts a variable or string into a number | `Number("10")` → `10` |
| `parseInt(string)` | Parses string and returns a whole integer | `parseInt("10.33")` → `10` |
| `parseFloat(string)` | Parses string and returns a floating-point number | `parseFloat("10.33")` → `10.33` |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Formatting numbers
let num = 9.656;

console.log(num.toFixed(0)); // "10"
console.log(num.toFixed(2)); // "9.66"
console.log(num.toPrecision(2)); // "9.7"

// Converting strings/booleans to numbers
console.log(Number(true));       // 1
console.log(Number("10.33"));    // 10.33
console.log(Number("10 20"));    // NaN

// Parsing integers and floats from text
console.log(parseInt("-10.33"));  // -10
console.log(parseInt("10 20 30"));// 10 (returns first number)
console.log(parseFloat("10.33")); // 10.33

// Check integer status (ES6)
console.log(Number.isInteger(10));   // true
console.log(Number.isInteger(10.5)); // false
```
</details>

---

## Remember

- All number formatting methods (`toFixed()`, `toPrecision()`, `toExponential()`) return a **string**.
- `parseInt()` and `parseFloat()` ignore trailing non-numeric characters if a valid number comes first.
- `Number()` returns `NaN` if the entire string cannot be parsed into a valid number.
- `Number()` can also convert date objects into milliseconds elapsed since Jan 1, 1970.
- Modern JavaScript ES6 provides `Number.isInteger()` to check if a value is a whole integer.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
