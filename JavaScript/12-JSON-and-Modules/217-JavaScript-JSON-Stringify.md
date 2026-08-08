# JavaScript JSON Stringify

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-JSON_Stringify-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JSON.stringify() converts a JavaScript value into a JSON-formatted string for storage or transmission.**

</div>

---

## Quick Summary

- JSON.stringify() converts JavaScript objects and arrays to JSON strings.
- Functions, undefined, and Symbol values are excluded from the output.
- A replacer parameter can filter or transform output properties.
- A space parameter adds indentation for human-readable formatted output.
- Dates are automatically converted to ISO 8601 string format.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **JSON.stringify(obj)** | Returns compact JSON string from object. |
| **Replacer Array** | Only includes listed property names in output. |
| **Replacer Function** | Transforms each key-value pair during serialization. |
| **Space Parameter** | Adds indentation spaces for pretty-print formatting. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
JSON.stringify(value, replacer, space)
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create a JavaScript object

const person = {

  name: "John",

  age: 30,

  city: "New York"

};



// Convert the object to a JSON text

const text = JSON.stringify(person);
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create a JavaScript array

const cars = ["Ford", "Volvo", "BMW"];



// Convert the array to a JSON text

const text = JSON.stringify(cars);
```
</details>

---

## Remember

- undefined, functions, and Symbol properties are silently dropped from JSON output.
- Circular references cause JSON.stringify() to throw a TypeError.
- JSON.stringify(obj, null, 2) produces nicely indented JSON output.
- Use toJSON() method on an object to control its JSON serialization behavior.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
