# JavaScript Function Closures

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Closures-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**A closure is a function that remembers and accesses variables from its outer enclosing scope even after outer function finishes.**

</div>

---

## Quick Summary

- A closure gives an inner function access to an outer function variables scope.
- In JavaScript, closures are created every time a function is created at creation time.
- Outer function variables remain persistent in memory as long as the closure exists.
- Enables creating private variables and data encapsulation in JavaScript.
- Commonly formed when an inner function is returned from an outer function.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Closure Definition** | Function bundled together with references to its surrounding state. |
| **Private State** | Variables inside outer function cannot be accessed directly except via closure. |
| **Scope Preservation** | Outer scope variables persist even after outer function returns. |
| **Stateful Functions** | Functions maintain private state between calls. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function myFunction() {

    let a = 4;

    return a * a;

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let a = 4;
function myFunction() {

    return a * a;

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function myFunction() {

  a = 4;

}
```
</details>

---

## Remember

- Closures retain access to outer function variables, not just snapshots.
- Useful for creating private counters, instance data, or factory functions.
- Be mindful of memory retention if holding closures unnecessarily.
- Inner functions have access to global variables, outer function variables, and local variables.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
