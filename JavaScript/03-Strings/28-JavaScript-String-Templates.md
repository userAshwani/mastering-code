# JavaScript String Templates

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-String_Templates-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Template literals use backticks to allow quotes, multi-line strings, and variable interpolation.**

</div>

---

## Quick Summary

- Template literals use backticks (`` ` ``) instead of quotes (`'` or `"`).
- You can use both single and double quotes inside a template literal.
- Template literals support multi-line strings without special break characters.
- Variables and expressions are evaluated directly using `${expression}` syntax.
- Useful for creating dynamic HTML markup and inline math expressions.

---

## Key Points

| Feature | Regular Strings (`" "` / `' '`) | Template Literals (`` ` ` ``) |
| :--- | :--- | :--- |
| **Delimiters** | Single `'` or double `"` quotes | Backticks `` ` `` |
| **Quotes Inside** | Must be escaped (`\'`, `\"`) | Allowed without escaping |
| **Multi-line** | Requires `\n` or `+` operator | Native multi-line support |
| **Interpolation** | Requires `+` concatenation | `${variable}` syntax |
| **Expressions** | Calculated outside string | Evaluated inside `${...}` |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Quotes inside template literals
let text = `He's often called "Johnny"`;

// Multi-line string
let bio = `The quick brown fox
jumps over
the lazy dog`;

// Variable interpolation
let firstName = "John";
let lastName = "Doe";
let greeting = `Welcome ${firstName}, ${lastName}!`;

// Expression evaluation inside template literal
let price = 10;
let vat = 0.25;
let total = `Total: ${(price * (1 + vat)).toFixed(2)}`;

// HTML template construction
let header = "Templates";
let tags = ["template literals", "javascript", "es6"];
let html = `<h2>${header}</h2><ul>`;

for (const x of tags) {
  html += `<li>${x}</li>`;
}
html += `</ul>`;
```
</details>

---

## Remember

- Always use backticks (`` ` ``) located near the ~ key on your keyboard.
- Use `${}` syntax to embed variables or expressions directly into strings.
- Expressions inside `${}` are evaluated and converted to a string automatically.
- Template literals maintain line breaks and whitespace exactly as typed.
- String templates were introduced in ES6 (JavaScript 2015).

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
