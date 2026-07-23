# JavaScript Comparisons

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Comparisons-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript comparison operators compare values and return `true` or `false`.**

</div>

---

## Quick Summary

- Comparison operators compare two values.
- Comparisons always return `true` or `false`.
- `==` checks equal value.
- `===` checks equal value and equal type.
- String values can also be compared.

---

## Key Points

| Operator | Simple Meaning |
| :--- | :--- |
| `==` | Equal to |
| `===` | Equal value and equal type |
| `!=` | Not equal |
| `!==` | Not equal value or not equal type |
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greater than or equal to |
| `<=` | Less than or equal to |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let x = 5;

console.log(x == 5);
console.log(x === "5");
console.log(x > 8);
console.log(x < 8);
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let text1 = "A";
let text2 = "B";
let result = text1 < text2;

console.log(result);
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
age = Number(age);

if (isNaN(age)) {
  voteable = "Input is not a number";
} else {
  voteable = (age < 18) ? "Too young" : "Old enough";
}
```
</details>

---

## Remember

- Comparison results are boolean values.
- `==` allows value comparison.
- `===` checks both value and type.
- Strings are compared alphabetically.
- Comparing different data types may give unexpected results.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
