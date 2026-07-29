# JavaScript Temporal PlainDateTime

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal.PlainDateTime stores a date and time without a time zone.**

</div>

---

## Quick Summary

- PlainDateTime includes date and clock time.
- It does not include a time zone.
- It is useful for local date-time values.
- It can be created from date-time strings.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| Date | Year, month, and day. |
| Time | Hour, minute, second, and more. |
| Time Zone | Not included. |
| Calendar | Can include calendar information. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const dt = Temporal.PlainDateTime.from("2025-03-25T10:30");
```
</details>

---

## Remember

- PlainDateTime is not tied to a time zone.
- Use it when local date and time are enough.
- Use ZonedDateTime when zone matters.
- It combines date and clock time.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

