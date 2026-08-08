# JavaScript Function Apply

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Apply-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The apply() method invokes a function with a specified this object and arguments provided as an array.**

</div>

---

## Quick Summary

- apply() is similar to call(), but accepts arguments as a single array or array-like object.
- The first argument specifies the object to use as this inside the function.
- The second argument is an array containing all parameters to pass to the function.
- Useful for passing arrays to functions expecting individual arguments (like Math.max).
- Executes the function immediately upon calling.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **fn.apply(ownerObj, [args])** | Invokes fn with this set to ownerObj and arguments array. |
| **Math.max.apply(null, arr)** | Finds maximum number in an array. |
| **Array Arguments** | Accepts parameters packaged as a single array. |
| **call vs apply** | call() takes comma list; apply() takes an array. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
functionName.apply(this, [arg1, arg2, ...]);
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


greet.apply(person3, ["Hello"]);
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
greet.call(person, "Hello");

greet.apply(person, ["Hello"]);
```
</details>

---

## Remember

- apply() takes arguments as an array: apply(obj, [arg1, arg2]).
- Useful when the number of arguments is dynamic or stored in an array.
- Modern spread operator (...arr) often replaces apply() for array arguments.
- Executes the function immediately when called.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
