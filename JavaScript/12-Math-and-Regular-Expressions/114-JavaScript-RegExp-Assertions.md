# JavaScript RegExp Assertions

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Assertions match positions in text.**

</div>

---

## Quick Summary

- Assertions test text positions.
- `^` checks the start.
- `$` checks the end.
- Lookahead checks following text.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `^` | Beginning. |
| `$` | End. |
| `(?=...)` | Positive lookahead. |
| `(?!...)` | Negative lookahead. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let text = "Hello world";
let result = /^Hello/.test(text);
```
</details>

---

## Remember

- Assertions check positions.
- Use `^` for starts.
- Use `$` for ends.
- Lookaheads inspect nearby text.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
