# JavaScript Object Reference

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Object_Reference-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript Object reference lists all built-in Object constructor methods and instance methods.**

</div>

---

## Quick Summary

- Object constructor methods like assign(), keys(), and freeze() operate on objects directly.
- Object.create() creates a new object using a specified prototype.
- Object.defineProperty() and defineProperties() configure property descriptors.
- Object.getOwnPropertyNames() lists all own property names including non-enumerable ones.
- Instance methods like toString() and valueOf() are inherited via Object.prototype.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Object.assign()** | Copies properties from sources to target object. |
| **Object.create()** | Creates object with specified prototype. |
| **Object.getOwnPropertyNames()** | Returns all own property names (including non-enumerable). |
| **Object.prototype.hasOwnProperty()** | Checks if property is own (not inherited). |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Example illustrating JavaScript Object Reference
console.log("JavaScript Object Reference demo");
```
</details>

---

## Remember

- Static methods on Object constructor are called as Object.methodName().
- Instance methods are inherited from Object.prototype by all objects.
- Object.keys() only lists enumerable own properties unlike getOwnPropertyNames().
- Object.is() performs strict equality comparison handling NaN and -0 correctly.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
