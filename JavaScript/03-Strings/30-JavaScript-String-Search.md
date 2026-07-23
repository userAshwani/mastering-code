# JavaScript String Search

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-String_Search-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**String search methods locate text, check occurrences, and match patterns in strings.**

</div>

---

## Quick Summary

- Use `indexOf()` and `lastIndexOf()` to find the index position of text.
- Use `includes()` to check if a string contains a value (`true` or `false`).
- Use `startsWith()` and `endsWith()` to check the start or end of text.
- Use `search()` for regex pattern index searches without start positions.
- Use `match()` and `matchAll()` to extract regex pattern matches into arrays.

---

## Key Points

| Method | Returns | Description |
| :--- | :--- | :--- |
| `indexOf(text)` | Index position (or `-1`) | Returns index of first occurrence |
| `lastIndexOf(text)` | Index position (or `-1`) | Returns index of last occurrence |
| `includes(text)` | `true` / `false` | Checks if text exists in string |
| `startsWith(text)` | `true` / `false` | Checks if string starts with text |
| `endsWith(text)` | `true` / `false` | Checks if string ends with text |
| `search(pattern)` | Index position (or `-1`) | Searches using string or Regular Expression |
| `match(pattern)` | Array (or `null`) | Returns array of matching strings |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let text = "Please locate where 'locate' occurs!";

// Finding index position
console.log(text.indexOf("locate"));     // 7
console.log(text.lastIndexOf("locate")); // 21
console.log(text.indexOf("John"));       // -1

// Checking boolean presence
console.log(text.includes("where"));     // true
console.log(text.startsWith("Please"));  // true
console.log(text.endsWith("occurs!"));   // true

// Searching with Regex
console.log(text.search(/locate/));      // 7

// Matching pattern matches
let str = "The rain in SPAIN stays mainly in the plain";
let matches = str.match(/ain/g);
console.log(matches); // ["ain", "ain", "ain"]
```
</details>

---

## Remember

- `indexOf()` and `lastIndexOf()` return `-1` if the search text is not found.
- `indexOf()` accepts a 2nd parameter specifying the starting search position.
- `search()` accepts regular expressions but does not accept a start position parameter.
- `includes()`, `startsWith()`, and `endsWith()` are case-sensitive methods.
- Both `startsWith()` and `endsWith()` accept optional position parameters.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
