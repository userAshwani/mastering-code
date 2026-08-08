# JavaScript Object Accessors

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Object_Accessors-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript getters and setters allow defining computed properties with controlled access.**

</div>

---

## Quick Summary

- Getter (get) is a method that retrieves a computed property value.
- Setter (set) is a method that assigns a value to a property with validation logic.
- Getters and setters are defined using the get and set keywords inside objects.
- They provide simpler property access syntax compared to explicit method calls.
- Object.defineProperty() can also add getters and setters to existing objects.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **get keyword** | Defines a getter that reads a computed property. |
| **set keyword** | Defines a setter that sets a property value. |
| **Object.defineProperty()** | Adds accessor descriptor to existing object. |
| **Advantage** | Cleaner syntax; hides implementation from external code. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Create an object:

const person = {

  firstName: "John",

  lastName: "Doe",

  language: "en",

  get lang() {

    return this.language;

    }
};


// Display data from the object using a getter:

document.getElementById("demo").innerHTML = person.lang;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {

  firstName: "John",

  lastName: "Doe",

  language: "",

    set lang(lang) {

    this.language = lang;

    }
};


// Set an object 
property using a setter:

person.lang = "en";


// Display data from the object:

document.getElementById("demo").innerHTML = person.language;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const person = {

  firstName: "John",

  lastName: "Doe",

  fullName: function() {

    return this.firstName + " " + 
this.lastName;
  }

};

// Display data from the object using a method:

  document.getElementById("demo").innerHTML = person.fullName();
```
</details>

---

## Remember

- Getters are accessed like regular properties — no parentheses needed.
- Setters receive the assigned value as their parameter.
- Accessors defined in class bodies work the same way as in object literals.
- Use getters to derive or compute values from existing properties.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
