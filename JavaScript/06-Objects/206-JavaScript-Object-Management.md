# JavaScript Object Management

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Object_Management-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript provides built-in methods for managing, converting, and copying object data.**

</div>

---

## Quick Summary

- Object.assign() copies enumerable own properties from source objects to a target object.
- Spread syntax {...source} creates a shallow clone of an object.
- Object.keys() and Object.entries() extract property names or pairs from objects.
- delete operator removes a property and its value from an object.
- in operator checks if a property exists anywhere in an object prototype chain.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Object.assign(target, src)** | Copies properties from source to target object. |
| **{...source}** | Spread to shallow-clone or merge objects. |
| **delete obj.prop** | Removes property from object. |
| **"prop" in obj** | Checks for property existence including prototype chain. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Adding or changing an object property

Object.defineProperty(object, property, descriptor)


// Adding or changing object properties

Object.defineProperties(object, descriptors)


// Accessing a Property

Object.getOwnPropertyDescriptor(object, property)


// Accessing Properties

Object.getOwnPropertyDescriptors(object)


// Returns all properties as an array

Object.getOwnPropertyNames(object)


// Accessing the prototype

Object.getPrototypeOf(object)
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
Object.defineProperty(object, property, descriptor)
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create an Object:
const person = {
  firstName: "John",
  lastName : 
  "Doe",
  language : "EN"
};

// Add a Property
Object.defineProperty(person, "year", 
  {value:"2008"});
```
</details>

---

## Remember

- Object.assign() performs a shallow copy, not a deep clone.
- Spread syntax also performs a shallow copy of object properties.
- The delete operator returns true even if the property does not exist.
- Use JSON.parse(JSON.stringify(obj)) for simple deep clone of plain objects.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
