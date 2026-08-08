# JavaScript JSON Introduction

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-JSON_Introduction-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JSON (JavaScript Object Notation) is a lightweight text format for storing and transporting structured data.**

</div>

---

## Quick Summary

- JSON stands for JavaScript Object Notation.
- JSON is a lightweight text format used for data exchange between servers and browsers.
- JSON uses key-value pair syntax similar to JavaScript object literal notation.
- JSON.parse() converts a JSON string into a JavaScript object.
- JSON.stringify() converts a JavaScript object into a JSON string.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **JSON.parse()** | Parses a JSON string and returns a JavaScript object. |
| **JSON.stringify()** | Converts JavaScript object to a JSON formatted string. |
| **Key Format** | JSON keys must always be double-quoted strings. |
| **Data Types** | Supports string, number, object, array, boolean, and null. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
{

  "name": "John",

  "age": 30,

  "city": "New York"

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {

  name: "John",

  age: 30,

  city: "New York"

};
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
{

  "name": "John",

  "age": 30,

  "city": "New York"

}
```
</details>

---

## Remember

- JSON keys and string values must use double quotes — single quotes are invalid.
- JSON does not support functions, undefined, or Symbol values.
- JSON is language-independent and used across many programming languages.
- JSON.parse() throws a SyntaxError if the string is invalid JSON.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
