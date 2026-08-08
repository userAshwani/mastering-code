# JavaScript Function Advanced Quiz

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Quiz-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Advanced Function Quiz tests comprehension of function concepts, scopes, closures, and invocation modes.**

</div>

---

## Quick Summary

- Tests understanding of function declarations vs expressions and hoisting.
- Evaluates knowledge of this binding across method, standalone, and arrow functions.
- Assesses understanding of call(), apply(), and bind() method execution.
- Verifies closure scope retention and private state management.
- Reinforces best practices for writing clean modular function logic.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Hoisting Quiz** | Distinguish hoisted declarations from non-hoisted expressions. |
| **this Context** | Verify this value in method, event, and arrow function calls. |
| **Closures Quiz** | Predict state variable outputs in returned inner functions. |
| **Invocation Modes** | Check results of call(), apply(), and bind() execution. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {

  name: "John",

  getName: function() {

    return this.name;

  }

};


person.getName();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const getName = person.getName;

getName();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = { name: "John" };

function getName() { return this.name; }
```
</details>

---

## Remember

- Reviewing function quizzes solidifies understanding of execution contexts.
- Always test arrow function this behavior vs standard function calls.
- Understand when closures retain mutable state variables.
- Mastering functions is essential for proficient JavaScript development.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
