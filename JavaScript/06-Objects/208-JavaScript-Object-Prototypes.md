# JavaScript Object Prototypes

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Object_Prototypes-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Every JavaScript object has a prototype which allows sharing properties and methods via inheritance.**

</div>

---

## Quick Summary

- Every JavaScript object has a built-in property called prototype.
- Objects inherit properties and methods from their prototype.
- Prototype chain is the lookup path used when accessing object properties.
- Object.getPrototypeOf() returns the prototype object of a given object.
- Adding to Constructor.prototype makes the property available to all instances.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Prototype Chain** | JS looks up prototype chain when property is not found. |
| **Constructor.prototype** | Properties/methods added here are shared by all instances. |
| **Object.getPrototypeOf()** | Returns the prototype of the given object. |
| **__proto__** | Informal property pointing to object prototype (deprecated). |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function Person(first, last, age, eyecolor) {

   
this.firstName = first;

  this.lastName = last;

   
this.age = age;

   
this.eyeColor = eyecolor;

}


const myFather = new Person("John", "Doe", 50, "blue");

const myMother = new Person("Sally", "Rally", 48, "green");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
Person.nationality = "English";
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function Person(first, last, age, eyecolor) {

   
this.firstName = first;

   
this.lastName = last;

   
this.age = age;

   
this.eyeColor = eyecolor;
  this.nationality = "English";

}
```
</details>

---

## Remember

- Do not modify the prototype of built-in JavaScript objects in production.
- hasOwnProperty() checks if a property belongs to the object itself, not its prototype.
- Classes in JavaScript use prototypes behind the scenes.
- Object.create(proto) creates a new object inheriting from the specified prototype.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
