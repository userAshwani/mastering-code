# JavaScript String Methods

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-String_Methods-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**String methods help you manipulate, extract, transform, and inspect string text.**

</div>

---

## Quick Summary

- Strings are immutable: methods return new strings without modifying the original.
- Use `slice()`, `substring()`, or `substr()` to extract parts of a string.
- Use `toUpperCase()` and `toLowerCase()` to convert letter case.
- Use `trim()`, `trimStart()`, and `trimEnd()` to remove extra whitespace.
- Use `split()` to convert a string into an array of substrings.

---

## Key Points

| Method | Description | Example |
| :--- | :--- | :--- |
| `charAt(index)` | Returns character at specified index | `"Cat".charAt(0)` → `"C"` |
| `slice(start, end)` | Extracts a section of a string | `"Apple".slice(0, 3)` → `"App"` |
| `substring(start, end)` | Similar to `slice`, negative values treated as 0 | `"Hello".substring(1, 4)` → `"ell"` |
| `toUpperCase()` | Converts string to uppercase letters | `"hi".toUpperCase()` → `"HI"` |
| `trim()` | Removes whitespace from both ends | `" text ".trim()` → `"text"` |
| `replace(search, replace)` | Replaces first match with a new string | `"a b".replace("a", "x")` → `"x b"` |
| `split(separator)` | Splits a string into an array | `"a,b".split(",")` → `["a", "b"]` |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Extracting string parts
let text = "Apple, Banana, Kiwi";
let part = text.slice(7, 13); // "Banana"

// Case conversion
let greeting = "Hello World!";
console.log(greeting.toUpperCase()); // "HELLO WORLD!"
console.log(greeting.toLowerCase()); // "hello world!"

// String trimming & padding
let padded = "5";
console.log(padded.padStart(4, "0")); // "0005"

let paddedEnd = "5";
console.log(paddedEnd.padEnd(4, "0")); // "5000"

// Replacing text
let sentence = "Please visit Microsoft!";
let newSentence = sentence.replace("Microsoft", "JavaScript");

// Splitting string to array
let csv = "HTML,CSS,JavaScript";
let arr = csv.split(","); // ["HTML", "CSS", "JavaScript"]
```
</details>

---

## Remember

- All string methods return a **new string** and do not change the original variable.
- Indexing starts at `0`: the first character is at position `0`.
- Negative parameters in `slice()` count backwards from the end of the string.
- `replace()` is case-sensitive and only replaces the **first** match unless a regex with `/g` is used.
- `split("")` with an empty string splits text into an array of individual characters.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
