# JavaScript Function IIFE

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_IIFE-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**An IIFE (Immediately Invoked Function Expression) is a function that runs immediately after definition.**

</div>

---

## Quick Summary

- IIFE stands for Immediately Invoked Function Expression.
- Defined using grouping parentheses (function() {})() to run instantly.
- Creates a private lexical scope preventing variable leakage to the global scope.
- Variables declared inside an IIFE cannot be accessed from outside.
- Avoids global scope pollution in legacy scripts and module patterns.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **(function() {})()** | Standard syntax for an anonymous IIFE. |
| **Private Scope** | Variables declared inside IIFE remain isolated. |
| **Immediate Execution** | Function runs instantly at definition time. |
| **Global Cleanliness** | Prevents polluting window global scope. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
(function () {

  // Code to run immediately

})();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
(function () {

  let x = 10;

})();


// x is not accessible here
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
(function () {

  let hidden = 42;

})();



let result = hidden; // &#9940; Error: hidden is not defined
```
</details>

---

## Remember

- First set of () converts the function into an expression.
- Second set of () invokes the function expression immediately.
- IIFE returns values just like regular functions.
- ES6 modules and block scope (let/const) largely reduce IIFE necessity today.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
