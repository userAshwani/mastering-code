# JavaScript Temporal Instant

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal.Instant represents one exact moment in time.**

</div>

---

## Quick Summary

- Instant is an exact point on the timeline.
- It is independent of calendar display.
- It can be converted to zoned date-time values.
- It is useful when exact time matters.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| Exact Moment | One point in time. |
| Time Zone | Not stored as a local zone. |
| Conversion | Can be shown in a specific zone. |
| Precision | Supports precise timestamp values. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const instant = Temporal.Now.instant();
```
</details>

---

## Remember

- Use Instant for exact timestamps.
- Instant is not a calendar date by itself.
- Convert it when display needs a time zone.
- It represents a fixed point in time.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

