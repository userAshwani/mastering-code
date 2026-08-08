# JavaScript Class Inheritance

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Class_Inheritance-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Class inheritance allows a child class to extend a parent class and reuse its properties and methods.**

</div>

---

## Quick Summary

- extends keyword creates a child class that inherits from a parent class.
- super() must be called in the constructor of the child class before using this.
- Child class can override parent class methods with its own implementation.
- super.methodName() calls the parent version of an overridden method.
- instanceof operator checks if an object is an instance of a class or its parent.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **extends** | Creates inheritance relationship between child and parent class. |
| **super()** | Calls parent class constructor before this is accessible. |
| **Method Override** | Child defines method with same name to replace parent. |
| **instanceof** | Checks class membership in prototype chain. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
class Car {
  constructor(brand) {
    this.carname = 
  brand;
 
  }
  present() {
    return 'I have a ' + this.carname;
 
  }
}

class Model extends Car {
 
  constructor(brand, mod) {
    super(brand);
    this.model = mod;
 
  }
  show() {
   
      return this.present() + ', it is a ' + this.model;
 
  }
}

let myCar = new Model("Ford", "Mustang");
document.getElementById("demo").innerHTML 
  = myCar.show();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
class Car {
  constructor(brand) {
    this.carname 
  = brand;
  }
  get cnam() {
    
  return this.carname;
  }
  set cnam(x) {
    
  this.carname = x;
  }
}

const myCar = new Car("Ford");


  document.getElementById("demo").innerHTML = myCar.cnam;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
class Car {
  constructor(brand) {
    this._carname 
  = brand;
  }
  get carname() {
    
  return this._carname;
  }
  set carname(x) {
    
  this._carname = x;
  }
}

const myCar = new Car("Ford");


  document.getElementById("demo").innerHTML = myCar.carname;
```
</details>

---

## Remember

- super() must be the first statement inside a child class constructor.
- Extending built-in objects like Array or Error is supported in modern JS.
- Child class inherits all non-private parent class properties and methods.
- Multiple inheritance (multiple extends) is not directly supported in JavaScript.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
