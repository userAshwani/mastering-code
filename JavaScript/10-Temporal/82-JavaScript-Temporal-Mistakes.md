# JavaScript Temporal Mistakes

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Common Temporal mistakes usually come from choosing the wrong type.**

</div>

---

## Quick Summary

- Use the right Temporal object for the job.
- Do not use plain types when time zones matter.
- Do not use Instant when a calendar date is needed.
- Be clear about date-only and date-time values.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| Wrong Type | Can make logic confusing. |
| Missing Zone | Causes problems when zone matters. |
| Plain Values | Do not include time zones. |
| Instant | Represents exact time, not a calendar-only date. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const dateOnly = Temporal.PlainDate.from("2025-03-25");
```
</details>

---

## Remember

- Pick the Temporal type first.
- Use ZonedDateTime for zone-aware values.
- Use PlainDate for date-only values.
- Use Instant for exact timeline points.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

