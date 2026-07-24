# JavaScript Function Return

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Return-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The `return` statement stops a function and sends a value back to the caller.**

</div>

---

## Quick Summary

- Use `return` to send a value back from a function.
- Code after `return` inside a function is **never executed**.
- A function without a `return` statement returns `undefined` by default.
- You can use `return` to exit a function early (e.g., inside a condition).
- The returned value can be stored in a variable or used directly in an expression.

---

## Key Points

| Concept | Description |
| :--- | :--- |
| **`return` statement** | Exits the function and sends a value back |
| **No `return`** | Function returns `undefined` automatically |
| **Early exit** | `return` can stop a function before it finishes |
| **Return value** | Can be a number, string, boolean, object, or expression |
| **Use in expression** | Returned value can be used directly without storing it |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Basic return — send a value back
function multiply(a, b) {
  return a * b;
}

let result = multiply(4, 3);
console.log(result); // 12
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Code after return is never reached
function myFunction(a, b) {
  return a * b;
  console.log("This line never runs"); // unreachable
}
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Using return to exit early
function checkAge(age) {
  if (age < 18) {
    return "Too young";
  }
  return "Welcome!";
}

checkAge(15); // "Too young"
checkAge(21); // "Welcome!"
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Using the returned value directly in an expression
function toCelsius(f) {
  return (5 / 9) * (f - 32);
}

// Use the return value directly
let text = "Temperature: " + toCelsius(77) + " Celsius";
console.log(text); // "Temperature: 25 Celsius"
```

</details>

---

## Remember

- `return` immediately stops the function — no more code runs after it.
- A function can have **multiple** `return` statements (e.g., inside `if/else`).
- If `return` has no value (just `return;`), the function returns `undefined`.
- Returned values can be passed directly to other functions or expressions.
- Always use `return` when you need a function to produce a result.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
