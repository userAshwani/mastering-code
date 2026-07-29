# JavaScript Temporal Differences

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal difference methods calculate the distance between values.**

</div>

---

## Quick Summary

- Temporal can compare two values by difference.
- `since()` calculates time since another value.
- `until()` calculates time until another value.
- The result is a Duration.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `since()` | Difference from another value to this value. |
| `until()` | Difference from this value to another value. |
| Result | A Temporal.Duration. |
| Units | Can be date or time units. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const start = Temporal.PlainDate.from("2025-03-01");
const end = Temporal.PlainDate.from("2025-03-25");
const diff = start.until(end);
```
</details>

---

## Remember

- Use differences to measure time between values.
- The result is a duration.
- Choose `since()` or `until()` based on direction.
- Difference methods keep time spans clear.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

