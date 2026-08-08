# JavaScript Object Iterations

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Object_Iterations-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript provides multiple methods to iterate over object keys, values, and entries.**

</div>

---

## Quick Summary

- for...in loop iterates over all enumerable property names of an object.
- Object.keys() returns an array of an object own enumerable property keys.
- Object.values() returns an array of an object own enumerable property values.
- Object.entries() returns an array of [key, value] pairs from the object.
- Object.fromEntries() converts a list of [key, value] pairs back into an object.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **for...in** | Iterates over all enumerable property names including inherited. |
| **Object.keys(obj)** | Array of own enumerable property name strings. |
| **Object.values(obj)** | Array of own enumerable property values. |
| **Object.entries(obj)** | Array of own [key, value] pair arrays. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Copies properties from a source object to a target object

Object.assign(target, source)


// Creates an object from an existing object

Object.create(object)


// Returns an array of the key/value pairs of an object

Object.entries(object)


// Creates an object from a list of keys/values

Object.fromEntries()


// Returns an array of the keys of an object

Object.keys(object)


// Returns an array of the property values of an object

Object.values(object)


// Groups object elements according to a function

Object.groupBy(object, callback)
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create Target Object

const person1 = {

  firstName: "John",

  lastName: "Doe",

  age: 50,

  eyeColor: "blue"

};



// Create Source Object

const person2 = {firstName: "Anne",lastName: "Smith"};



// Assign Source to Target

Object.assign(person1, person2);
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {

  firstName : "John",

  lastName : "Doe",

  age : 50,

  eyeColor : "blue"

};



let text = Object.entries(person);
```
</details>

---

## Remember

- for...in includes inherited properties; use hasOwnProperty() to filter.
- Object.keys(), values(), entries() only return own enumerable properties.
- Spread operator {...obj} can shallow-copy enumerable own properties.
- Object.fromEntries(map) is useful for converting Map to plain object.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
