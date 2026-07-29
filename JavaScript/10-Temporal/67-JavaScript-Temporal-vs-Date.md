# JavaScript Temporal vs Date

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Temporal separates date and time concepts more clearly than the older Date object.**

</div>

---

## Quick Summary

- Date stores a timestamp with built-in limitations.
- Temporal provides multiple focused object types.
- Temporal handles time zones more clearly.
- Temporal avoids many Date parsing and mutation issues.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `Date` | Older built-in date object. |
| `Temporal` | Modern date and time API. |
| Mutation | Date objects can be changed. |
| Clear Types | Temporal has separate types for different needs. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const date = new Date();
const temporalDate = Temporal.Now.plainDateISO();
```
</details>

---

## Remember

- Date and Temporal are different APIs.
- Temporal is more explicit.
- Use Temporal types based on the value needed.
- Date code often mixes different date-time concepts.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>

