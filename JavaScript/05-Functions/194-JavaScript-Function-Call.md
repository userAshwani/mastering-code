# JavaScript Function Call

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Call-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The call() method invokes a function by explicitly specifying the this object and individual arguments.**

</div>

---

## Quick Summary

- call() is a predefined JavaScript method present on all function objects.
- Allows an object to use a method belonging to another object (method borrowing).
- The first argument to call() specifies the object to be used as this.
- Additional arguments are passed to call() individually separated by commas.
- Executes the function immediately with the bound this context.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **fn.call(ownerObj)** | Invokes fn setting this to ownerObj. |
| **fn.call(ownerObj, arg1, arg2)** | Passes additional arguments individually. |
| **Method Borrowing** | Reuses a method from one object on a different object. |
| **Immediate Execution** | call() runs the target function immediately when called. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
functionName.call(this, arg1, arg2, ...);
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



function greet(greeting) {

  return greeting + " " + this.name;

}



greet.call(person3, "Hello");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {

    fullName: function() {

    return this.firstName + " " + this.lastName;

    }
}

const person1 = {

  firstName:"John",

    lastName: "Doe"

  }

const person2 = {

  firstName:"Mary",

    lastName: "Doe"
}



// This will return "John Doe":
  
  person.fullName.call(person1);
```
</details>

---

## Remember

- First argument of call() becomes the this context inside the function.
- Arguments after ownerObj are passed individually: call(obj, a, b, c).
- In strict mode, first argument becomes this even if primitive or null.
- Enables object method reuse without code duplication.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
