# JavaScript Functions

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Functions-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**A function is a block of code designed to perform a particular task — run it whenever you call it.**

</div>

---

## Quick Summary

- A function is defined with the `function` keyword, a name, and `()`.
- Code inside `{}` runs only when the function is **called** (invoked).
- You can pass data into a function using **parameters**.
- A function can send a result back using the `return` statement.
- Functions let you reuse the same code many times with different inputs.

---

## Key Points

| Concept | Description |
| :--- | :--- |
| **Function definition** | Declares the function using `function name() {}` |
| **Function call** | Executes the function: `name()` |
| **Parameters** | Variables listed inside `()` in the definition |
| **Arguments** | Actual values passed when calling the function |
| **Return value** | The result sent back using `return` |
| **Local variables** | Variables declared inside a function — not accessible outside |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Define a function with two parameters
function myFunction(p1, p2) {
  return p1 * p2; // returns the product
}

// Call the function and store the result
let result = myFunction(4, 3);
console.log(result); // 12
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Function without return — just performs an action
function greet(name) {
  console.log("Hello, " + name + "!");
}

greet("Ashwani"); // Hello, Ashwani!
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Local variable — exists only inside the function
function showCount() {
  let count = 5; // local variable
  return count;
}

// console.log(count); // ❌ ReferenceError: count is not defined
```

</details>

---

## Remember

- The `()` operator **invokes** the function — without it, you just reference the function object itself.
- Parameters act like local variables inside the function.
- If a function has no `return` statement, it returns `undefined` by default.
- Variables declared inside a function are **local** — they only exist within that function.
- The same function can be called many times with **different arguments**.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
