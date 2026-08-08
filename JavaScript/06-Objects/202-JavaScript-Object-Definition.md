# JavaScript Object Definition

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Object_Definition-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript objects can be defined using object literals, new Object(), or constructor functions.**

</div>

---

## Quick Summary

- An object literal { } is the simplest way to create a JavaScript object.
- new Object() creates an empty object which can then have properties added to it.
- Constructor functions create reusable object templates with the new keyword.
- Object.create() creates a new object using an existing object as prototype.
- Objects store properties as key-value pairs and methods as function values.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Object Literal** | const obj = { key: value } — simplest object creation. |
| **new Object()** | Creates empty object; properties added afterward. |
| **Constructor Function** | function Person(name) { this.name = name; } |
| **Object.create()** | Creates object inheriting from specified prototype. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
{firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create an Object

const person = {

  firstName: "John",

  lastName: "Doe",

  age: 50,

  eyeColor: "blue"

};
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create an Object

const person = new Object({

  firstName: "John",

  lastName: "Doe",

  age: 50,

  eyeColor: "blue"
 
});
```
</details>

---

## Remember

- Object literal notation is the most common and readable way to define objects.
- Constructor functions use this to assign properties to the new object instance.
- Objects are reference types; two variables can point to the same object.
- Object.create(null) creates an object with no prototype chain.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
