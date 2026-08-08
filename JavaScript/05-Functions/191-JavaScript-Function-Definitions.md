# JavaScript Function Definitions

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Definitions-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript functions are defined using function declarations, function expressions, or Function() constructors.**

</div>

---

## Quick Summary

- Function declarations use the function keyword and are hoisted to the top of their scope.
- Function expressions store anonymous functions inside variable declarations.
- Function expressions are not hoisted and must be defined before calling.
- Function constructor (new Function()) creates functions dynamically from strings.
- Self-invoking function expressions run automatically when defined.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Function Declaration** | function name() {} — hoisted automatically. |
| **Function Expression** | const x = function() {} — not hoisted. |
| **Function Constructor** | new Function("a", "b", "return a * b") |
| **Self-Invoking (IIFE)** | (function() {})() — executes immediately. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Function Declaration

function myFunction(x, y) {

  return x * y;

}



// Function Expression (Named)

const myFunction = function name(x, y) {

  return x * y;

};



// Function Expression (Anonymous)

const myFunction = function (x, y) {

  return x * y;

};



// Arrow Function

const myFunction = (x, y) => x * y;



// Function Constructor

const myFunction = new Function("x", "y", "return x * y");



// Object Method

const obj = {

  myFunction(x, y) {

    return x * y;

  },

};
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function functionName(parameters) {

  // code to be executed

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function myFunction(a, b) {return a * b}
```
</details>

---

## Remember

- Declarations are hoisted; expressions are not hoisted.
- Function constructor usage is discouraged due to performance and security concerns.
- Functions can be declared inside blocks, objects, or expressions.
- Semicolons end function expression statements, not function declarations.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
