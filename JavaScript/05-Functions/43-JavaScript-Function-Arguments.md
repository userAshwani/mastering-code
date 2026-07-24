# JavaScript Function Arguments

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Arguments-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Function arguments are the actual values passed into parameters when a function is called.**

</div>

---

## Quick Summary

- Arguments are real values passed to a function when it is invoked.
- Missing arguments default to `undefined`, while extra arguments are accessible via `arguments`.
- Default parameters allow setting fallback values when arguments are omitted.
- Primitive arguments are passed by **value**, while objects are passed by **reference**.
- The rest parameter (`...`) gathers an indefinite number of arguments into an array.

---

## Key Points

| Concept | Description |
| :--- | :--- |
| **Parameters vs Arguments** | Parameters are names in the definition; arguments are actual values passed. |
| **Arguments Object** | Built-in array-like object containing all arguments passed to the function. |
| **Default Parameters** | Assigns default values to parameters if arguments are missing or `undefined`. |
| **Rest Parameters (`...`)** | Collects remaining arguments into a single array parameter. |
| **Pass by Value** | Primitive arguments cannot be changed outside the function. |
| **Pass by Reference** | Object arguments can have their properties changed outside the function. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Parameters vs Arguments
function multiply(a, b) {
  return a * b; // a and b are parameters
}

let result = multiply(4, 5); // 4 and 5 are arguments
console.log(result); // 20
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// The arguments object — finding maximum value
function findMax() {
  let max = -Infinity;
  for (let i = 0; i < arguments.length; i++) {
    if (arguments[i] > max) {
      max = arguments[i];
    }
  }
  return max;
}

let x = findMax(1, 123, 500, 115, 44, 88);
console.log(x); // 500
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Default parameter values
function addNumbers(x, y = 10) {
  return x + y;
}

console.log(addNumbers(5));     // 15 (y defaults to 10)
console.log(addNumbers(5, 20)); // 25
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Rest parameters (...)
function sum(...args) {
  let sum = 0;
  for (let arg of args) {
    sum += arg;
  }
  return sum;
}

let x = sum(4, 9, 16, 25, 29);
console.log(x); // 83
```

</details>

---

## Remember

- Arguments are assigned to parameters strictly by position in the order they appear.
- JavaScript does not perform type checking or argument count checking on functions.
- Primitive arguments are passed by value, so original variables remain unchanged.
- Object arguments are passed by reference, so modifying object properties affects the original.
- Default parameters and rest parameters make handling arguments clean and flexible.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
