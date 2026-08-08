# JavaScript This Keyword

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-This_Keyword-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The this keyword refers to the current execution context object in JavaScript.**

</div>

---

## Quick Summary

- In a method, this refers to the owning object of that method.
- In a standalone function, this refers to the global object (window in browsers).
- In strict mode, this inside a function is undefined.
- In an event handler, this refers to the HTML element that triggered the event.
- Arrow functions do not bind their own this; they inherit from the enclosing scope.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Object Method** | this refers to the object owning the method. |
| **Global Context** | this is the global window object outside any function. |
| **Strict Mode** | this is undefined inside plain functions in strict mode. |
| **Arrow Functions** | Inherit this from the lexical enclosing scope. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {

    firstName: "John",

  lastName : "Doe",

    id       : 5566,

    fullName : function() {

      return this.firstName + " " + this.lastName;

    }

};
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {

    firstName  : "John",

    lastName   : "Doe",

    id         : 5566,

    myFunction : function() {

    return this;
  }

};
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {

    firstName: "John",

    lastName : "Doe",

    id       : 5566,

    fullName : function() {

    return this.firstName + " " + 
this.lastName;
  }

};
```
</details>

---

## Remember

- this is determined by how a function is called, not where it is defined.
- call(), apply(), and bind() can explicitly override the this value.
- Arrow functions are not suitable as object methods if they need this.
- In class constructors, this refers to the newly created instance.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
