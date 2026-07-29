# JavaScript RegExp Characters

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Regular expression characters describe what text to match.**

</div>

---

## Quick Summary

- Characters can match exact text.
- Character sets match listed characters.
- Ranges match characters between values.
- Alternatives can match one option.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `[abc]` | One listed character. |
| `[0-9]` | One digit. |
| `(x|y)` | Either option. |
| Character | Literal or special. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let text = "Is this all there is?";
let result = text.match(/[h]/g);
```
</details>

---

## Remember

- Use brackets for sets.
- Use ranges for grouped values.
- Use `|` for alternatives.
- Characters form the pattern.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
