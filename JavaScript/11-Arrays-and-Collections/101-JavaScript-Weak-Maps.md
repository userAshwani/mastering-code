# JavaScript Weak Maps

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**A WeakMap stores object keys weakly.**

</div>

---

## Quick Summary

- WeakMap keys must be objects.
- WeakMap keys are held weakly.
- WeakMap is not enumerable.
- WeakMap has fewer methods than Map.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| WeakMap | Stores object keys with values. |
| Object Keys | Required. |
| `set()` | Adds a key-value pair. |
| `get()` | Reads a value by object key. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

`javascript
const weakMap = new WeakMap();
const obj = {};
weakMap.set(obj, "hello");
`
</details>

---

## Remember

- WeakMap keys must be objects.
- WeakMaps are not looped like Maps.
- Use `has()` to check an object key.
- Use `delete()` to remove an object key.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
