# JavaScript Date Get Methods

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Date get methods read parts of a Date object.**

</div>

---

## Quick Summary

- Get methods return parts of a date.
- You can get year, month, day, hour, minute, second, and millisecond.
- `getMonth()` returns `0` to `11`.
- `getDay()` returns weekday numbers from `0` to `6`.

---

## Key Points

| Method | Returns |
| :--- | :--- |
| `getFullYear()` | Year as four digits. |
| `getMonth()` | Month number from `0` to `11`. |
| `getDate()` | Day of the month. |
| `getDay()` | Day of the week from `0` to `6`. |
| `getHours()` | Hour from `0` to `23`. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const d = new Date("2021-03-25");
let year = d.getFullYear();
```
</details>

---

## Remember

- Get methods read values from dates.
- Month numbers start at `0`.
- Weekday numbers start at Sunday as `0`.
- UTC get methods are also available.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
