# JavaScript Function Bind

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Bind-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The bind() method creates a new function with a permanently bound this keyword and initial parameters.**

</div>

---

## Quick Summary

- bind() creates a new function that, when called, has its this keyword set to the provided object.
- Unlike call() or apply(), bind() does not execute the function immediately.
- Returns a copy of the target function with bound context.
- Prevents loss of this when passing object methods as callbacks or event handlers.
- Allows presetting initial arguments (function currying).

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **fn.bind(ownerObj)** | Returns a new function permanently bound to ownerObj. |
| **Preserving this** | Prevents losing this when passing methods to setTimeout. |
| **Delayed Execution** | Returns bound function reference to be called later. |
| **Argument Presetting** | Can preset lead arguments for future function calls. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const newFunction = functionName.bind(this, arg1, arg2, ...);
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person1 = { name: "John" };

const person2 = { name: "Paul" };

const person3 = { name: "Ringo" };



function greet() {

  return "Hello " + this.name;

}


const greetJohn = greet.bind(person1);


greetJohn();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create person Object

const person = {

  firstName:"John",

  lastName: "Doe",

    fullName: function () {

    return this.firstName + " " + this.lastName;

    }

}



// Create member Object

const member = {

  firstName:"Hege",

  lastName: "Nilsen",

}



// Bind the fullName method to the member Object
 
let fullName = person.fullName.bind(member);



// Later call fullname()

fullname()
```
</details>

---

## Remember

- bind() returns a new function; it does not execute the original function.
- Solves the problem of this becoming undefined inside asynchronous callbacks.
- The bound this value cannot be overridden by subsequent call() or apply().
- Ideal for passing class or object methods as event handlers.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
