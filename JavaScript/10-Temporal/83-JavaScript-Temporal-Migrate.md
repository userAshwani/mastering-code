# JavaScript Temporal Migrate

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Migrating to Temporal means replacing Date patterns with clearer Temporal types.**

</div>

---

## Quick Summary

- Date code can be moved to Temporal types.
- Choose the Temporal type that matches the old use case.
- Use Instant for exact timestamps.
- Use PlainDate or PlainDateTime for calendar values.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| Old Date Use | Possible Temporal Type |
| Timestamp | `Temporal.Instant` |
| Date Only | `Temporal.PlainDate` |
| Date and Time | `Temporal.PlainDateTime` |
| Date, Time, Zone | `Temporal.ZonedDateTime` |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const instant = Temporal.Instant.from("2025-03-25T10:30:00Z");
```
</details>

---

## Remember

- Do not replace all Date usage with one Temporal type.
- Match the type to the data.
- Use explicit conversions where needed.
- Temporal makes date-time intent clearer.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

