# JavaScript Array Const

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Arrays declared with `const` can still have their contents changed.**

</div>

---

## Quick Summary

- A `const` array cannot be reassigned.
- Array elements can still be changed.
- Items can still be added.
- Items can still be removed.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `const` Array | Keeps the variable reference fixed. |
| Change Element | Allowed. |
| Add Element | Allowed. |
| Reassign Array | Not allowed. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

`javascript
const cars = ["Saab", "Volvo", "BMW"];
cars[0] = "Toyota";
cars.push("Audi");
`
</details>

---

## Remember

- `const` does not make array items fixed.
- You can change array contents.
- You cannot assign a new array to the same const variable.
- Declare arrays with `const` when the variable should not be reassigned.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
