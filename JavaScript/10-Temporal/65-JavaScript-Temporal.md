# JavaScript Temporal

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal is a modern JavaScript API for working with dates and times.**

</div>

---

## Quick Summary

- Temporal provides modern date and time objects.
- It handles dates, times, durations, and time zones.
- It avoids many old Date object problems.
- Temporal has separate object types for separate jobs.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `Temporal.Now` | Gets current date and time values. |
| `Temporal.Instant` | Represents an exact moment in time. |
| `Temporal.Duration` | Represents an amount of time. |
| Plain types | Represent dates or times without time zones. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const now = Temporal.Now.plainDateISO();
```
</details>

---

## Remember

- Temporal is designed for clearer date and time work.
- Use the object type that matches the job.
- Plain date/time values do not include a time zone.
- Instant values represent exact points in time.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

