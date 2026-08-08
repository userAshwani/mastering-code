# JavaScript JSON and HTML

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-JSON_and_HTML-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JSON data can be parsed and dynamically injected into HTML elements to display dynamic content.**

</div>

---

## Quick Summary

- JSON data fetched from an API can be used to build and update HTML content.
- innerHTML is commonly used to inject parsed JSON data into HTML elements.
- Loop over parsed JSON arrays to generate repeated HTML list or table rows.
- JSON objects map naturally to HTML element properties and text content.
- DOM manipulation combined with JSON enables dynamic page rendering.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **innerHTML** | Set element HTML content from parsed JSON data string. |
| **Array Loop** | Iterate JSON array to generate multiple HTML elements. |
| **createElement()** | Build DOM nodes dynamically from JSON property values. |
| **JSON to Table** | Map JSON array to HTML table rows for data display. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const text = '{"name":"John","age":30,"city":"New York"}';


const person = JSON.parse(text);


document.getElementById("demo").textContent = person.name;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const text = '{"name":"John","age":30,"city":"New York"}';


const person = JSON.parse(text);


document.getElementById("demo").textContent =

person.name + ", " + person.age + ", " + person.city;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {name: "John", age: 30};


myDisplayer(person);
```
</details>

---

## Remember

- Always parse the JSON string before accessing its properties in JavaScript.
- Sanitize JSON string values before injecting them as innerHTML to prevent XSS.
- JSON arrays can be looped using forEach() or for...of to build HTML markup.
- Template literals make it easy to embed parsed JSON values into HTML strings.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
