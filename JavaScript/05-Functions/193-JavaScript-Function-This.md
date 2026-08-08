# JavaScript Function This

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_This-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The this keyword refers to the object that is executing the current function.**

</div>

---

## Quick Summary

- In an object method, this refers to the owner object.
- In a standalone function, this refers to the global object (window) or undefined in strict mode.
- In an event handler, this refers to the HTML element that received the event.
- Methods like call(), apply(), and bind() can explicitly set the value of this.
- Arrow functions do not have their own this binding; they inherit this from outer scope.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Method Invocation** | this refers to the object calling the method. |
| **Function Invocation** | this refers to global window (or undefined in strict mode). |
| **Explicit Binding** | call() and apply() bind this explicitly to specified object. |
| **Arrow Functions** | this is lexically inherited from outer enclosing scope. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {

  firstName: "John",

  lastName: "Doe",

  fullName: function() {

    return this.firstName + " " + this.lastName;

  }

};


person.fullName();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function myFunction() {

    return this;

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
"use strict";

function myFunction() {

  return this;

}
```
</details>

---

## Remember

- this is not a variable; you cannot reassign the value of this.
- How a function is called determines the value of this at runtime.
- Strict mode ("use strict") sets unattached function this to undefined.
- Arrow functions derive this from where they were defined, not called.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
