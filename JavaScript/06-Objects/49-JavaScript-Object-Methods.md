# JavaScript Object Methods

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Object_Methods-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Object methods are functions stored as object properties.**

</div>

---

## Quick Summary

- Methods are actions stored inside objects.
- A method is a function property.
- Methods can use `this`.
- A method is called with parentheses.

---

## Key Points

| Item | Simple Meaning |
| :--- | :--- |
| Method | A function inside an object. |
| `this` | Refers to the object. |
| `object.method()` | Calls a method. |
| Function property | A property that stores a function. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {
  firstName: "John",
  lastName: "Doe",
  fullName: function() {
    return this.firstName + " " + this.lastName;
  }
};

console.log(person.fullName());
```
</details>

---

## Remember

- Methods are object actions.
- Methods are written as functions.
- Use parentheses to run a method.
- `this` can access object properties.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
