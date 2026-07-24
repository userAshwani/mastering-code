# JavaScript Function Parameters

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Function_Parameters-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Function parameters are the names listed in the definition; arguments are the actual values passed when calling.**

</div>

---

## Quick Summary

- **Parameters** are placeholders declared in the function definition.
- **Arguments** are the real values you send when you call the function.
- If fewer arguments than parameters are passed, the missing ones are `undefined`.
- JavaScript functions have a built-in `arguments` object that holds all passed values.
- JavaScript does **not** perform type checking or argument count checking on parameters.

---

## Key Points

| Concept | Description |
| :--- | :--- |
| **Parameter** | Variable name in the function definition `(a, b)` |
| **Argument** | Actual value passed at call time `myFunc(1, 2)` |
| **Default value** | If no argument is given, the parameter is `undefined` |
| **`arguments` object** | Array-like object holding all arguments passed |
| **Pass by value** | Primitive values are copied — original is not changed |
| **Pass by reference** | Objects are passed by reference — original can change |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Parameters: x and y
// Arguments: 5 and 10
function add(x, y) {
  return x + y;
}

add(5, 10); // 15
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Missing argument defaults to undefined
function greet(name) {
  return "Hello, " + name;
}

greet("Ashwani"); // "Hello, Ashwani"
greet();          // "Hello, undefined"
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Using the arguments object
function sumAll() {
  let total = 0;
  for (let i = 0; i < arguments.length; i++) {
    total += arguments[i];
  }
  return total;
}

sumAll(1, 2, 3, 4); // 10
```

</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Primitives are passed by value — original is NOT changed
function changeValue(x) {
  x = 100;
}

let num = 10;
changeValue(num);
console.log(num); // 10 — unchanged

// Objects are passed by reference — original CAN change
function changeObj(obj) {
  obj.value = 100;
}

let myObj = { value: 10 };
changeObj(myObj);
console.log(myObj.value); // 100 — changed
```

</details>

---

## Remember

- JavaScript does **not** check the number of arguments — extra ones are ignored, missing ones are `undefined`.
- The `arguments` object contains all arguments passed, even those without a matching parameter.
- Primitive types (number, string, boolean) are passed **by value** — safe to modify locally.
- Objects and arrays are passed **by reference** — changes inside the function affect the original.
- There is no concept of `required` or `optional` parameters in vanilla JavaScript.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
