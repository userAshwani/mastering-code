# JavaScript Object Protection

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Object_Protection-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript provides Object.freeze(), Object.seal(), and property descriptors to protect object data.**

</div>

---

## Quick Summary

- Object.preventExtensions() stops new properties from being added to an object.
- Object.seal() prevents adding or deleting properties but allows updating existing ones.
- Object.freeze() prevents all modifications — no add, delete, or update of properties.
- Object.isExtensible() checks if new properties can be added.
- Object.isFrozen() and Object.isSealed() check protection state.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Object.preventExtensions()** | Blocks adding new properties. |
| **Object.seal()** | Blocks add/delete; allows editing existing values. |
| **Object.freeze()** | Fully immutable — no add, delete, or change. |
| **Object.isFrozen()** | Returns true if object is frozen. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Prevents re-assignment

const car = {type:"Fiat", model:"500", color:"white"};



// Prevents adding object properties

Object.preventExtensions(object)


// Returns true if properties can be added to an object

Object.isExtensible(object)


// Prevents adding and deleting object properties

Object.seal(object)


// Returns true if object is sealed

Object.isSealed(object)


// Prevents any changes to an object

Object.freeze(object)


// Returns true if object is frozen

Object.isFrozen(object)
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create Object

const person = {firstName:"John", lastName:"Doe"};



// Prevent Extensions

Object.preventExtensions(person);



// This will throw an error

person.nationality = "English";
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create Array

const fruits = ["Banana", "Orange", "Apple", "Mango"];

Object.preventExtensions(fruits);



// This will throw an error:

fruits.push("Kiwi");
```
</details>

---

## Remember

- Object.freeze() does not deep-freeze nested objects automatically.
- In strict mode, attempting to mutate a frozen object throws a TypeError.
- Sealed objects retain their existing property descriptors.
- These methods are useful for protecting constants or configuration objects.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
