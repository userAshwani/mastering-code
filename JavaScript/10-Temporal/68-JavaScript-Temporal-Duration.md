# JavaScript Temporal Duration

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal.Duration represents an amount of time.**

</div>

---

## Quick Summary

- Duration stores time amounts like days or hours.
- Durations can be added to Temporal values.
- Durations can be subtracted from Temporal values.
- A duration is not a specific date.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| Years | Larger calendar amount. |
| Months | Calendar-based amount. |
| Days | Day-based amount. |
| Hours/Minutes | Time-based amount. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const duration = Temporal.Duration.from({ days: 7 });
```
</details>

---

## Remember

- Use Duration for time spans.
- A duration is not a moment in time.
- Durations can include date and time units.
- Use clear units when creating durations.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

