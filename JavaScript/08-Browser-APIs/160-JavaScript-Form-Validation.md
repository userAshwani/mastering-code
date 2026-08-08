# JavaScript Form Validation

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Form_Validation-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Form validation checks user inputs to ensure required fields are correctly completed before submission.**

</div>

---

## Quick Summary

- HTML form validation can prevent submission if required input fields are empty.
- Automatic HTML5 validation uses attributes like required, min, max, and pattern.
- JavaScript can intercept form submit events to validate complex inputs.
- checkValidity() returns true if an input element contains valid data.
- validationMessage contains the browser message when validation fails.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **checkValidity()** | Returns true if input element passes validation rules. |
| **validationMessage** | Contains the error message displayed by the browser. |
| **willValidate** | Indicates if an element is subject to validation. |
| **setCustomValidity()** | Sets a custom validation error message on an input. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function validateForm() {

&nbsp;&nbsp;let
x = document.forms["myForm"]["fname"].value;

  &nbsp;
if (x == "") {

  &nbsp;&nbsp;&nbsp; alert("Name must be filled out");

  &nbsp;&nbsp;&nbsp; return false;

  &nbsp;&nbsp;}

}
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<form name="myForm" action="/action_page.php" onsubmit="return validateForm()" 
method="post">

 Name: <input type="text" name="fname">

<input type="submit" value="Submit">

</form>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<form action="/action_page.php" method="post">

&nbsp; <input type="text" name="fname" required>

&nbsp;
<input type="submit" value="Submit">

</form>
```
</details>

---

## Remember

- Form validation can occur client-side using HTML5 attributes or custom JavaScript.
- preventing submit on invalid forms prevents bad data reaching servers.
- checkValidity() can be called on forms or individual input elements.
- Always validate data on the server side as well for security.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
