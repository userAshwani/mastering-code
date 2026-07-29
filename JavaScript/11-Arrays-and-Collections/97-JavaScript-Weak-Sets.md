# JavaScript Weak Sets

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**A WeakSet stores objects weakly and only accepts objects.**

</div>

---

## Quick Summary

- WeakSet values must be objects.
- WeakSet values are held weakly.
- WeakSet is not enumerable.
- WeakSet has fewer methods than Set.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| WeakSet | Collection of weakly held objects. |
| Objects Only | Primitive values are not allowed. |
| `add()` | Adds an object. |
| `has()` | Checks for an object. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

`javascript
const weakSet = new WeakSet();
const obj = {};
weakSet.add(obj);
`
</details>

---

## Remember

- WeakSets only store objects.
- They are not looped like normal Sets.
- Use `has()` to check an object.
- Use `delete()` to remove an object.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
