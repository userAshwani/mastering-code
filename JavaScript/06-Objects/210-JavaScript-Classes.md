# JavaScript Classes

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Classes-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript classes are syntactic sugar over prototype-based inheritance providing cleaner OOP syntax.**

</div>

---

## Quick Summary

- A class is defined using the class keyword and acts as a template for objects.
- The constructor() method is called automatically when a new class instance is created.
- Class methods are defined directly inside the class body without function keyword.
- class expressions can be named or anonymous and assigned to variables.
- Classes are not hoisted — they must be defined before use.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **class keyword** | Defines a class template for creating objects. |
| **constructor()** | Special method called automatically on new instance creation. |
| **Class Method** | Functions defined inside class body on prototype. |
| **Not Hoisted** | Classes must be declared before being used. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
class ClassName {

   constructor() { ... }

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
class Car {

   constructor(name, year) {

    this.name = name;

    this.year = year;

  }

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const myCar1 = new Car("Ford", 2014);

const myCar2 = new Car("Audi", 2019);
```
</details>

---

## Remember

- Class declarations are not hoisted unlike function declarations.
- Class body code always executes in strict mode automatically.
- You can add methods to a class after definition using Class.prototype.method.
- Classes are primarily syntactic sugar — JavaScript still uses prototypes internally.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
