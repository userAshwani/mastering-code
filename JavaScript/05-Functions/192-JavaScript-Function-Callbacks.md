# JavaScript Function Callbacks

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Callbacks-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**A callback is a function passed as an argument into another function to be executed later.**

</div>

---

## Quick Summary

- A callback function is passed as a parameter to another function.
- The outer function calls the callback when a specific task or asynchronous action completes.
- Callbacks control execution order in asynchronous programming.
- Passing function names as callbacks should be done without parenthesis.
- Commonly used in array iteration, event listeners, and timer routines.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Callback Function** | Function passed as an argument to another function. |
| **Asynchronous Callback** | Executes after an async action (timers, fetch) completes. |
| **Synchronous Callback** | Executes immediately during outer function execution. |
| **Pass Without ()** | Pass fn instead of fn() to pass function reference. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.getElementById("myButton").addEventListener("click", displayDate);
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
setTimeout(myFunction, 3000);



function myFunction() {

  document.getElementById("demo").innerHTML = "I love You !!";

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const numbers = [45, 4, 9, 16, 25];

let txt = "";

numbers.forEach(myFunction);


function myFunction(value) {

   
txt += value + "<br>"; 

}
```
</details>

---

## Remember

- Pass the function name without () when supplying a callback.
- Using () invokes the function immediately rather than passing its reference.
- Callbacks ensure code runs only after an asynchronous operation finishes.
- Avoid callback hell by keeping nested callbacks modular.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
