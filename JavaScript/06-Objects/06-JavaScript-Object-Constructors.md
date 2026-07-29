# JavaScript Object Constructors

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Object_Constructors-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Object constructors create many objects with the same structure.**

</div>

---

## Quick Summary

- Constructor functions are used to create objects.
- Constructor names often start with a capital letter.
- `this` sets properties on the new object.
- The `new` keyword creates a new object.

---

## Key Points

| Item | Simple Meaning |
| :--- | :--- |
| Constructor | Function used to create objects. |
| `new` | Creates a new object. |
| `this` | Refers to the new object. |
| Property | Value added to the object. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function Person(first, last, age) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
}

const myFather = new Person("John", "Doe", 50);
console.log(myFather.firstName);
```
</details>

---

## Remember

- Constructors help create many similar objects.
- Use `new` with a constructor.
- `this` receives the new object.
- Constructor functions often use capitalized names.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
