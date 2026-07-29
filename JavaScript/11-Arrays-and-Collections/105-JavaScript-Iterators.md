# JavaScript Iterators

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Iterators provide a `next()` method for moving through values.**

</div>

---

## Quick Summary

- An iterator returns values one by one.
- `next()` returns the next result.
- Iterator results include `value` and `done`.
- Iteration stops when `done` is true.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| Iterator | Object that produces values. |
| `next()` | Gets the next result. |
| `value` | Current returned value. |
| `done` | Shows if iteration is complete. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

`javascript
const myIterator = ["a", "b", "c"].values();
let first = myIterator.next();
`
</details>

---

## Remember

- Iterators move through values step by step.
- Use `next()` to read the next item.
- `done` becomes true when finished.
- Iterable objects can create iterators.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
