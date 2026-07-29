# JavaScript Temporal Now

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal.Now provides current date and time values.**

</div>

---

## Quick Summary

- Temporal.Now returns current Temporal values.
- It can return an instant.
- It can return plain date or time values.
- It can use the system time zone.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `instant()` | Current exact instant. |
| `plainDateISO()` | Current ISO date. |
| `plainTimeISO()` | Current ISO time. |
| `zonedDateTimeISO()` | Current date-time with zone. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const now = Temporal.Now.instant();
```
</details>

---

## Remember

- Use Now methods for current values.
- Choose the method for the type needed.
- Plain values do not include time zones.
- Zoned values include time zone data.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

