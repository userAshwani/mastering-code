# JavaScript String Reference

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-String_Reference-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**A quick reference guide to built-in JavaScript String properties and methods.**

</div>

---

## Quick Summary

- String properties store string metadata such as character count (`length`).
- All string methods return a **new value** without mutating original strings.
- Methods handle character access, substring extraction, case formatting, and searching.
- Conversion methods turn other data structures into strings (`toString()`, `valueOf()`).
- HTML wrapper methods exist but are deprecated in modern JavaScript.

---

## Key Points

| Category | Key Methods / Properties | Purpose |
| :--- | :--- | :--- |
| **Properties** | `length`, `prototype`, `constructor` | String metadata and constructor access |
| **Character Access** | `at()`, `charAt()`, `charCodeAt()` | Returns character or character code at index |
| **Extraction** | `slice()`, `substring()`, `substr()` | Extracts parts of a string into a new string |
| **Transformation** | `toUpperCase()`, `toLowerCase()`, `trim()` | Alters case or strips surrounding whitespace |
| **Modification** | `concat()`, `replace()`, `padStart()`, `repeat()` | Joins, substitutes, pads, or duplicates text |
| **Inspection** | `indexOf()`, `includes()`, `startsWith()`, `match()` | Searches and checks for pattern occurrences |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let text = "JavaScript Reference";

// String Property
console.log(text.length); // 20

// Character inspection
console.log(text.at(0));        // "J"
console.log(text.charCodeAt(0));// 74

// String Transformation & Modification
console.log(text.toUpperCase());    // "JAVASCRIPT REFERENCE"
console.log(text.repeat(2));         // "JavaScript ReferenceJavaScript Reference"
console.log(text.replace("JavaScript", "JS")); // "JS Reference"

// Type conversion
let num = 100;
console.log(num.toString()); // "100"
```
</details>

---

## Remember

- JavaScript strings are **immutable** — string methods never modify the original string.
- `at()` supports negative index numbers to access characters from the end of a string.
- Prefer standard string methods over old HTML formatting methods like `bold()` or `italic()`.
- Use `valueOf()` or `toString()` to convert String objects to primitive string values.
- String indexes start at `0` for the first character.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
