# JavaScript JSON Data Types

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-JSON_Data_Types-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JSON supports six data types: string, number, object, array, boolean, and null.**

</div>

---

## Quick Summary

- JSON strings must be double-quoted Unicode sequences.
- JSON numbers can be integers or floating-point values (no octal or hex).
- JSON objects contain key-value pairs and can nest other JSON types.
- JSON arrays are ordered collections that can mix different JSON types.
- JSON boolean values are only true or false; JSON null represents empty value.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **String** | "Hello World" — must be double-quoted. |
| **Number** | 42 or 3.14 — no quotes, no leading zeros. |
| **Object** | { "key": "value" } — nested key-value structure. |
| **Array** | [1, "two", true] — ordered list of values. |

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
{
"employee":{"name":"John", "age":30, "city":"New York"}

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
{
"employees":["John", "Anna", "Peter"]
}
```
</details>

---

## Remember

- NaN and Infinity are not valid JSON number values.
- JSON arrays can contain mixed types: strings, numbers, objects, and arrays.
- JSON does not support undefined, functions, Date objects, or Symbols.
- Date objects are typically represented as ISO 8601 strings in JSON.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
