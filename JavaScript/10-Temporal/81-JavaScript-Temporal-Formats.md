# JavaScript Temporal Formats

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal formats turn date and time values into readable strings.**

</div>

---

## Quick Summary

- Temporal values can be formatted as strings.
- ISO-style strings are common.
- Formatting can show date, time, or zone details.
- String output depends on the Temporal type.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `toString()` | Converts a Temporal value to text. |
| Date Format | Shows calendar date. |
| Time Format | Shows clock time. |
| Zoned Format | Can include time zone details. |

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

- Use `toString()` for simple output.
- Different Temporal types format differently.
- Zoned values include zone information.
- Formatting helps display stored values.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

