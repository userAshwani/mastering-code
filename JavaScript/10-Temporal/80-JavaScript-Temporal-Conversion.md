# JavaScript Temporal Conversion

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal values can be converted between related date and time types.**

</div>

---

## Quick Summary

- Temporal objects have conversion methods.
- Values can be converted to strings.
- Some types can convert to related types.
- Conversion helps display or reshape values.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| To String | Converts value to text. |
| To Plain Date | Extracts date-only value. |
| To Plain Time | Extracts time-only value. |
| To Zoned Value | Adds zone when needed. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const dt = Temporal.PlainDateTime.from("2025-03-25T10:30");
const date = dt.toPlainDate();
```
</details>

---

## Remember

- Use conversion methods to change representation.
- String conversion is useful for display.
- Some conversions need extra information.
- Choose the target type clearly.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

