# JavaScript `this` in Objects

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-this_in_Objects-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**In an object method, `this` refers to the object that owns the method.**

</div>

---

## Quick Summary

- `this` refers to an object.
- In an object method, `this` refers to the object.
- `this` can access object properties.
- The value of `this` depends on how a function is called.

---

## Key Points

| Use | Simple Meaning |
| :--- | :--- |
| `this.firstName` | Current object's `firstName`. |
| `this.lastName` | Current object's `lastName`. |
| Object method | Common place to use `this`. |
| Function call | Can change what `this` means. |

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

- `this` is a keyword.
- In a method, `this` can mean the owner object.
- `this` is not a variable.
- The value of `this` can change in different situations.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
