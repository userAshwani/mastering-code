# JavaScript Function Invocation

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Invocation-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Function invocation is how and when a function is triggered — the way you call it changes what `this` refers to.**

</div>

---

## Quick Summary

- A function runs (is invoked) when it is **called** using `()`.
- How you call a function determines the value of `this` inside it.
- Functions can be invoked as **plain functions**, as **methods**, or as **constructors**.
- In a plain function call, `this` refers to the global object (or `undefined` in strict mode).
- When called as a method, `this` refers to the **object** that owns the method.

---

## Key Points

| Invocation Style | How It Looks | `this` Value |
| :--- | :--- | :--- |
| **As a function** | `myFunction()` | Global object (or `undefined` in strict mode) |
| **As a method** | `object.myMethod()` | The owner object |
| **As a constructor** | `new MyFunction()` | The newly created object |
| **Via call/apply** | `fn.call(obj)` | Whatever you pass in |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Invoking as a plain function
function myFunction(a, b) {
  return a * b;
}

myFunction(10, 2); // returns 20
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// this in a plain function call refers to the global object
function myFunction() {
  return this;
}

myFunction(); // returns the global object (e.g. window in browsers)
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Invoking as a method — this refers to the owner object
const myObject = {
  firstName: "John",
  lastName: "Doe",
  fullName: function () {
    return this.firstName + " " + this.lastName;
  }
};

myObject.fullName(); // "John Doe"
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Invoking as a constructor with new
function myFunction(arg1, arg2) {
  this.firstName = arg1;
  this.lastName = arg2;
}

// new creates a blank object; this refers to that new object
const myObj = new myFunction("John", "Doe");
myObj.firstName; // "John"
```

</details>

---

## Remember

- `this` in JavaScript is **not fixed** — it depends on how the function is called.
- In a plain function call, `this` is the **global object** (`window` in browsers).
- In **strict mode** (`"use strict"`), `this` inside a plain function is `undefined`.
- When a function is called as a **method**, `this` is the object before the dot.
- Using `new` makes `this` point to the **newly created object**.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
