# JavaScript Temporal Arithmetic

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal arithmetic adds or subtracts time from Temporal values.**

</div>

---

## Quick Summary

- Temporal values can use `add()`.
- Temporal values can use `subtract()`.
- Duration values define the amount.
- Arithmetic returns a new Temporal value.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `add()` | Adds a duration. |
| `subtract()` | Subtracts a duration. |
| Duration | Defines the amount to change. |
| Result | A changed Temporal value. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const date = Temporal.PlainDate.from("2025-03-25");
const nextWeek = date.add({ days: 7 });
```
</details>

---

## Remember

- Use `add()` to move forward.
- Use `subtract()` to move backward.
- Use clear duration units.
- Temporal arithmetic keeps date logic explicit.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

