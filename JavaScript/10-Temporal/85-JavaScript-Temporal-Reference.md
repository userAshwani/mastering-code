# JavaScript Temporal Reference

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal reference covers the main Temporal objects and methods.**

</div>

---

## Quick Summary

- Temporal includes several date and time object types.
- Reference methods create, compare, convert, and format values.
- Each object type has a specific purpose.
- Use the reference to choose the right API.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| Object | Purpose |
| `Temporal.Instant` | Exact moment. |
| `Temporal.Duration` | Amount of time. |
| `Temporal.PlainDate` | Date only. |
| `Temporal.ZonedDateTime` | Date-time with zone. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const date = Temporal.PlainDate.from("2025-03-25");
const text = date.toString();
```
</details>

---

## Remember

- Temporal has multiple focused objects.
- Use methods that match the object type.
- Reference pages help find available methods.
- Choose the Temporal type before writing logic.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

