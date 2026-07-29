# JavaScript RegExp Quantifiers

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Quantifiers define how many times a pattern should match.**

</div>

---

## Quick Summary

- Quantifiers control repetition.
- `+` matches one or more.
- `*` matches zero or more.
- `?` matches zero or one.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `n+` | One or more. |
| `n*` | Zero or more. |
| `n?` | Zero or one. |
| `n{X}` | Exactly X times. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let text = "Hellooo World";
let result = text.match(/o+/g);
```
</details>

---

## Remember

- Use quantifiers for repeated matches.
- `+` needs at least one.
- `*` can match none.
- Braces define counts.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
