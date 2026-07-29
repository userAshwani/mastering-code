# JavaScript Temporal Compare

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal comparison checks the order of Temporal values.**

</div>

---

## Quick Summary

- Temporal values can be compared.
- Compare returns ordering information.
- It helps sort date and time values.
- Matching Temporal types are easiest to compare.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `compare()` | Compares two values. |
| `-1` | First value is earlier. |
| `0` | Values are equal. |
| `1` | First value is later. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const a = Temporal.PlainDate.from("2025-03-01");
const b = Temporal.PlainDate.from("2025-03-25");
const result = Temporal.PlainDate.compare(a, b);
```
</details>

---

## Remember

- Use compare methods for ordering.
- Comparison can support sorting.
- A result of `0` means equal.
- Use matching Temporal types when possible.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

