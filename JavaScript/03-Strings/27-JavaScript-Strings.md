# JavaScript Strings

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Strings-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript strings are used for storing and manipulating text.**

</div>

---

## Quick Summary

- Strings store text written inside single (`'`), double (`"`), or backtick (`` ` ``) quotes.
- The `.length` property returns the total number of characters in a string.
- Escape characters (`\`) allow quotes and special characters inside text.
- Strings can be primitive values or created as objects using `new String()`.
- Primitive strings are faster and recommended over String objects.

---

## Key Points

| Concept | Description | Example |
| :--- | :--- | :--- |
| **Quotes** | Enclose text in quotes | `"Hello"`, `'World'`, `` `Text` `` |
| **String Length** | Returns string length count | `"JavaScript".length` (10) |
| **Escape Character** | Uses backslash `\` to escape quotes | `\"` or `\'` |
| **String Objects** | Created with `new String()` constructor | `new String("Text")` |
| **Object Comparison** | Comparing two String objects returns `false` | `x === y` (`false`) |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Creating strings with different quotes
let firstName = "John";
let lastName = 'Doe';
let text = `Welcome ${firstName} ${lastName}!`;

// String length property
let alphabet = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
console.log(alphabet.length); // 26

// Using escape sequences in text
let quote = "We are the so-called \"Vikings\" from the north.";
console.log(quote);

// Primitive string vs String object
let x = "John";             // string primitive
let y = new String("John"); // string object

console.log(typeof x); // "string"
console.log(typeof y); // "object"
console.log(x == y);   // true
console.log(x === y);  // false
```
</details>

---

## Remember

- Quotes inside text must not match the surrounding quotes unless escaped.
- Backslash `\` turns special characters into string text.
- Never create strings as objects with `new String()` due to performance loss.
- Comparing two JavaScript String objects with `==` or `===` always evaluates to `false`.
- Template literals (backticks `` ` ``) allow multi-line text and variable interpolation.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
