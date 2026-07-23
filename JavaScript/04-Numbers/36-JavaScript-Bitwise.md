# JavaScript Bitwise Operators

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Bitwise_Operators-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Bitwise operators convert numbers to 32-bit integers and operate on their binary bits.**

</div>

---

## Quick Summary

- Bitwise operations work directly on binary representation of 32-bit signed numbers.
- `&` (AND) sets each bit to 1 if both corresponding bits are 1.
- `|` (OR) sets each bit to 1 if at least one corresponding bit is 1.
- `^` (XOR) sets each bit to 1 if only one of two corresponding bits is 1.
- `~` (NOT) inverts all bits (flips 0s to 1s and 1s to 0s).

---

## Key Points

| Operator | Name | Description | Example |
| :--- | :--- | :--- | :--- |
| `&` | AND | Sets bit to 1 if both bits are 1 | `5 & 1` → `1` |
| `\|` | OR | Sets bit to 1 if either bit is 1 | `5 \| 1` → `5` |
| `^` | XOR | Sets bit to 1 if only one bit is 1 | `5 ^ 1` → `4` |
| `~` | NOT | Inverts all the bits | `~5` → `-6` |
| `<<` | Zero fill left shift | Shifts left, filling right side with 0s | `5 << 1` → `10` |
| `>>` | Signed right shift | Shifts right, preserving sign bit | `5 >> 1` → `2` |
| `>>>` | Zero fill right shift | Shifts right, filling left side with 0s | `5 >>> 1` → `2` |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Bitwise operations on 5 (0101) and 1 (0001)
console.log(5 & 1);  // 1  (0001)
console.log(5 | 1);  // 5  (0101)
console.log(5 ^ 1);  // 4  (0100)
console.log(~5);     // -6 (inverts bits)

// Bitwise shifts
console.log(5 << 1); // 10 (shifts left by 1 bit)
console.log(5 >> 1); // 2  (shifts right by 1 bit)

// Binary to Decimal and Decimal to Binary conversion
let dec = 5;
let bin = (dec >>> 0).toString(2); // Decimal to Binary: "101"
let num = parseInt("101", 2);       // Binary to Decimal: 5

console.log(bin); // "101"
console.log(num); // 5
```
</details>

---

## Remember

- JavaScript converts numbers to 32-bit signed integers before running bitwise operations.
- Results are converted back into standard JavaScript numbers after calculation.
- `~x` is equal to `-(x + 1)`.
- Left shift `x << y` is equivalent to multiplying `x` by $2^y$.
- Right shift `x >> y` is equivalent to integer dividing `x` by $2^y$.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
