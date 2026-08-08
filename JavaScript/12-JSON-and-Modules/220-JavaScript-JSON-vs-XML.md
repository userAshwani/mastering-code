# JavaScript JSON vs XML

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-JSON_vs_XML-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JSON and XML are both data interchange formats; JSON is simpler, lighter, and natively supported in JS.**

</div>

---

## Quick Summary

- JSON is shorter and easier to read and write compared to XML.
- XML uses closing tags making it more verbose; JSON uses brackets and braces.
- JSON is natively parsed by JavaScript; XML requires an XML parser object.
- JSON supports arrays directly; XML represents arrays as repeated elements.
- JSON does not support comments; XML supports comments within markup.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **JSON Parsing** | JSON.parse() — built into all modern browsers natively. |
| **XML Parsing** | Requires DOMParser or XMLHttpRequest XML mode. |
| **Verbosity** | XML has opening and closing tags; JSON uses { } and [ ]. |
| **Arrays** | JSON uses [ ]; XML repeats the same element tag multiple times. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
{

  "employees": [

    {"firstName":"John", "lastName":"Doe"},

    {"firstName":"Anna", "lastName":"Smith"},

    {"firstName":"Peter", "lastName":"Jones"}

  ]

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<employees>

  <employee>

    <firstName>John</firstName>

    <lastName>Doe</lastName>

  </employee>

  <employee>

    <firstName>Anna</firstName>

    <lastName>Smith</lastName>

  </employee>

  <employee>

    <firstName>Peter</firstName>

    <lastName>Jones</lastName>

  </employee>

</employees>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
{

  "name": "John",

  "skills": ["HTML", "CSS", "JavaScript"]

}
```
</details>

---

## Remember

- JSON is the preferred format for modern REST APIs due to its simplicity.
- XML is still used in legacy systems, SOAP APIs, and configuration files (like SVG).
- JSON does not support attributes; XML elements can have attribute key-value pairs.
- Both formats are plain text and can be transmitted over any HTTP connection.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
