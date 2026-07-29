# JavaScript Temporal PlainMonthDay

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal.PlainMonthDay stores a month and day without a year.**

</div>

---

## Quick Summary

- PlainMonthDay stores month and day.
- It does not focus on a specific year.
- It is useful for recurring calendar dates.
- It does not include time or time zone.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| Month | Stored. |
| Day | Stored. |
| Year | Not the main value. |
| Time | Not included. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const md = Temporal.PlainMonthDay.from("03-25");
```
</details>

---

## Remember

- Use it for month-day values.
- It can represent recurring dates.
- No time is stored.
- No time zone is stored.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

