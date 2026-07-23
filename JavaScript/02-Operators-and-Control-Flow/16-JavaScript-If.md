# JavaScript `if`

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-if-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The JavaScript `if` statement runs a block of code when a condition is true.**

</div>

---

## Quick Summary

- `if` runs code only when a condition is true.
- The condition is written inside parentheses.
- The code block is written inside curly braces.
- `if` must be written in lowercase.
- `if` statements can be nested.

---

## Key Points

| Item | Simple Meaning |
| :--- | :--- |
| `if` | Starts a conditional statement. |
| Condition | A true or false test. |
| Code block | The code that runs when the condition is true. |
| Lowercase rule | `If` or `IF` will cause an error. |
| Nested `if` | An `if` inside another `if`. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
if (hour < 18) {
  greeting = "Good day";
}
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let age = 18;
let text = "You can Not drive";

if (age >= 18) {
  text = "You can drive";
}
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let age = 16;
let country = "USA";
let text = "You can Not drive!";

if (country == "USA" && age >= 16) {
  text = "You can drive!";
}
```
</details>

---

## Remember

- Use `if` when code should run only for a true condition.
- Write `if` in lowercase.
- Curly braces hold the code to run.
- Nested `if` statements can make code more complex.
- `&&` can combine conditions.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
