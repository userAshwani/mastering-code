# JavaScript Function Introduction

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Intro-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Functions are reusable blocks of code designed to perform a task — they run only when called.**

</div>

---

## Quick Summary

- Use the `function` keyword followed by a name and `()` to define a function.
- The code inside `{}` does **not** run until the function is called.
- Call a function by writing its name followed by `()`.
- Functions can receive input (parameters) and return output (return value).
- Local variables inside a function are created when it runs and deleted when it finishes.

---

## Key Points

| Concept | Description |
| :--- | :--- |
| **Function keyword** | `function` starts every function definition |
| **Name** | Follows the same naming rules as variables |
| **Parameters** | Optional inputs listed inside `()` |
| **Body** | Code to run, placed inside `{}` |
| **Call / Invoke** | `functionName()` runs the function |
| **Return** | Sends a value back to the caller |
| **Local variable** | Exists only inside the function; deleted when done |
| **Reuse** | Call the same function many times with different inputs |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Define a function
function sayHello() {
  return "Hello World";
}

// Call the function
let message = sayHello();
console.log(message); // Hello World
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Function syntax with parameters
function multiply(a, b) {
  return a * b;
}

// Reuse the same function with different arguments
let result1 = multiply(3, 4);  // 12
let result2 = multiply(10, 5); // 50
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Local variable — only accessible inside the function
// code here can NOT use carName

function myFunction() {
  let carName = "Volvo";
  // code here CAN use carName
}

// code here can NOT use carName
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Functions can be used directly as variable values
// Instead of this:
let x = toCelsius(77);
let text1 = "The temperature is " + x + " Celsius";

// You can do this:
let text2 = "The temperature is " + toCelsius(77) + " Celsius";
```

</details>

---

## Remember

- `()` after a function name **invokes** it — without `()`, it just references the function object.
- A function definition is **not** an executable statement — it does not run on its own.
- It is not common to end a function definition with a semicolon.
- Variables with the same name can exist in different functions without conflict.
- The same function with different inputs can produce different results.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
