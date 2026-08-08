# JavaScript Async Callbacks

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Async_Callbacks-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Asynchronous callbacks allow functions to be called after an async operation completes its task.**

</div>

---

## Quick Summary

- A callback function is passed as an argument and called when an operation completes.
- setTimeout() is a common example of calling a callback after a delay.
- Callbacks are the traditional pattern for handling asynchronous operations.
- Deeply nested callbacks create callback hell making code hard to read.
- Promises and async/await were introduced to replace complex callback chains.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Callback Pattern** | Pass function as argument; call it when task completes. |
| **Error-first Callback** | First parameter is error, second is success data. |
| **Callback Hell** | Deeply nested callbacks that become hard to maintain. |
| **Async Callback** | Function called after async task finishes (setTimeout, fetch). |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// A Greet Function

function greet(name, callback) {

  callback("Hello " + name);

}



// A Display Function

function display(message) {

  document.getElementById("demo").innerHTML = message;

}



// Call greet() with a callback function (display)

greet("John", display);
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Calculate Function

function calculate(x, y, operation) {

  return operation(x, y);

}



// Add Function

function add(a, b) {

  return a + b;

}



// Call calculate() with add as callback

let result = calculate(5, 3, add);
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let result;



setTimeout(function() {

  result = 5;

}, 1000);



// What is result here?
```
</details>

---

## Remember

- Pass function references (no ()) when providing callbacks to async functions.
- Error-first callbacks (common in Node.js) pass error as the first parameter.
- Flat, named callback functions reduce nesting and improve code readability.
- Promises and async/await are preferred over raw callbacks for modern code.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
