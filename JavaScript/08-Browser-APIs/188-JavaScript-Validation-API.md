# JavaScript Validation API

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Validation_API-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The Constraint Validation API provides DOM properties and methods to validate input elements.**

</div>

---

## Quick Summary

- checkValidity() checks if an input element satisfies its constraint rules.
- validity property returns a ValidityState object containing detailed boolean validation flags.
- validity.valueMissing is true if a required input field is empty.
- validity.typeMismatch is true if value does not match input type (like email).
- setCustomValidity() sets a custom validation error message string.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **checkValidity()** | Returns true if element satisfies all validation rules. |
| **validity.valueMissing** | True if required input field has no value. |
| **validity.typeMismatch** | True if value fails type check (email/url). |
| **setCustomValidity()** | Sets custom error message string on element. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<input id="id1" type="number" min="100" max="300" 
    required>
<button onclick="myFunction()">OK</button>

<p id="demo"></p>

<script>

 function myFunction() {
  const inpObj = document.getElementById("id1");
  if (!inpObj.checkValidity()) {
    document.getElementById("demo").innerHTML = inpObj.validationMessage;

    }
}
</script>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<input id="id1" type="number" max="100">
<button onclick="myFunction()">OK</button>


<p id="demo"></p>


<script>

function myFunction() {
  let text = "Value OK";

    if (document.getElementById("id1").validity.rangeOverflow) {

      text = "Value too large";

    }

}

</script>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<input id="id1" type="number" min="100">

<button onclick="myFunction()">OK</button>


<p id="demo"></p>

<script>

function myFunction() {
  let text = "Value OK";

    if (document.getElementById("id1").validity.rangeUnderflow) {

      text = "Value too small";

    }

}
</script>
```
</details>

---

## Remember

- validity object provides detailed reasons why an input failed validation.
- Call setCustomValidity("") with an empty string to clear a custom error.
- validationMessage contains the current browser error message.
- Combines with CSS pseudo-classes :valid and :invalid for styling.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
