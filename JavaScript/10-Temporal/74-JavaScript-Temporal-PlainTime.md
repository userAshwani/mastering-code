# JavaScript Temporal PlainTime

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal.PlainTime stores a clock time without a date or time zone.**

</div>

---

## Quick Summary

- PlainTime stores time of day.
- It does not include a date.
- It does not include a time zone.
- It can store hour, minute, second, and smaller units.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| Hour | Stored. |
| Minute | Stored. |
| Second | Can be stored. |
| Date | Not included. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const time = Temporal.PlainTime.from("10:30:00");
```
</details>

---

## Remember

- Use PlainTime for clock-only values.
- No date is stored.
- No time zone is stored.
- It represents a time of day.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

