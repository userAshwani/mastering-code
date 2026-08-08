# JavaScript JSON Server

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-JSON_Server-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JSON is the standard format for exchanging data between client browser and web server APIs.**

</div>

---

## Quick Summary

- Servers send JSON-formatted responses to browser clients over HTTP.
- fetch() retrieves JSON data from a server and response.json() parses it.
- JSON.stringify() is used to serialize object data before sending to a server.
- HTTP Content-Type header should be set to application/json for JSON requests.
- REST APIs commonly use JSON for both request body and response body data.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **fetch(url)** | Makes HTTP GET request to retrieve JSON from server. |
| **response.json()** | Parses JSON response body into JavaScript object. |
| **POST with JSON** | Stringify object in body; set Content-Type header. |
| **Content-Type Header** | "application/json" signals JSON format to server. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
{

  "id": 101,

  "name": "John Doe",

  "city": "New York",

  "member": true

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
async function loadJSON() {


  const response = await fetch("customer.json");


  const customer = await response.json();



  myDisplayer(customer.name);


}



loadJSON();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
[

  {"name":"Laptop","price":899},

  {"name":"Mouse","price":29},

  {"name":"Keyboard","price":79}

]
```
</details>

---

## Remember

- response.json() returns a Promise; use await or .then() to resolve it.
- Always validate and sanitize JSON data received from external servers.
- JSON data from server APIs must be parsed before properties can be accessed.
- Set Content-Type: application/json header when posting JSON to REST APIs.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
