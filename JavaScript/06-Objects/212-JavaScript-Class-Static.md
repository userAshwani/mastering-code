# JavaScript Class Static

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Class_Static-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Static class methods and properties belong to the class itself rather than to class instances.**

</div>

---

## Quick Summary

- static keyword defines a method or property that belongs to the class, not instances.
- Static methods cannot be called on an object instance — only on the class itself.
- Static properties store class-level data shared across all instances.
- Static blocks allow running initialization code when the class is first defined.
- static fields can be public or private (using # prefix for private).

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **static Method** | Called on the class: ClassName.method() — not on instances. |
| **static Property** | Data stored on the class constructor, shared globally. |
| **Static Block** | Runs initialization code inside static {} when class loads. |
| **Private Static** | static #field declares private static class field. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
class Car {
  constructor(name) {
    this.name = 
  name;
 
  }
  static hello() {
    return "Hello!!";
 
  }
}

const myCar = new Car("Ford");

// You can call 'hello()' on 
  the Car Class:
document.getElementById("demo").innerHTML 
  = Car.hello();

// But NOT on a Car Object:
// document.getElementById("demo").innerHTML 
  = myCar.hello();
// this will raise an error.
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
class Car {
  constructor(name) {
    this.name = 
  name;
 
  }
  static hello(x) {
    return "Hello " + 
  x.name;
 
  }
}
const myCar = new Car("Ford");
document.getElementById("demo").innerHTML 
  = Car.hello(myCar);
```
</details>

---

## Remember

- Static methods are utility functions that do not require instance state.
- You cannot access static methods via this inside instance methods.
- Static properties are accessed via ClassName.propertyName.
- Static methods are inherited by child classes through the class prototype chain.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
