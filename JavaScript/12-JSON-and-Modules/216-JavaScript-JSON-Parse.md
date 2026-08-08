# JavaScript JSON Parse

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-JSON_Parse-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JSON.parse() converts a JSON string into a JavaScript object ready to be accessed in code.**

</div>

---

## Quick Summary

- JSON.parse() takes a JSON-formatted string and returns a JavaScript object or array.
- Parsed JSON objects can be accessed using dot notation or bracket notation.
- JSON.parse() accepts an optional reviver function to transform parsed values.
- Date strings parsed from JSON are returned as strings, not Date objects.
- JSON.parse() throws a SyntaxError if the input string is not valid JSON.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **JSON.parse(str)** | Converts JSON string to JavaScript object. |
| **Reviver Function** | Optional second parameter to transform values during parsing. |
| **Date Parsing** | Dates come back as strings; convert manually with new Date(). |
| **SyntaxError** | Thrown when the JSON string is invalid or malformed. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
JSON.parse(text, reviver)
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const text = '{"name":"John","age":30,"city":"New York"}';



const person = JSON.parse(text);



let name= person.name;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const text = '["Ford","Volvo","BMW"]';



const cars = JSON.parse(text);



let name= cars[0];
```
</details>

---

## Remember

- Always wrap JSON.parse() in try-catch when parsing data from external sources.
- Parsed JSON arrays are returned as JavaScript arrays with indexed access.
- The reviver function receives each key-value pair during the parse operation.
- JSON.parse() can parse arrays: JSON.parse("[1, 2, 3]") returns [1, 2, 3].

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
