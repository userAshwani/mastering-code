# JavaScript Display Objects

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Display_Objects-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript objects can be displayed by showing their properties or converting them to strings.**

</div>

---

## Quick Summary

- Displaying an object directly may show `[object Object]`.
- Object properties can be displayed one by one.
- Object values can be displayed with `Object.values()`.
- Objects can be converted to JSON strings.

---

## Key Points

| Method | Simple Meaning |
| :--- | :--- |
| `object.property` | Display one property. |
| Loop | Display many properties. |
| `Object.values()` | Get object values as an array. |
| `JSON.stringify()` | Convert object to a string. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {
  name: "John",
  age: 30,
  city: "New York"
};

console.log(person.name + ", " + person.age + ", " + person.city);
console.log(JSON.stringify(person));
```
</details>

---

## Remember

- Objects need formatting before display.
- Display properties directly for simple output.
- `Object.values()` returns values.
- `JSON.stringify()` turns an object into text.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
