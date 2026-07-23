# JavaScript Ternary Operator

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Ternary_Operator-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The ternary operator is a short way to write a simple `if...else` condition.**

</div>

---

## Quick Summary

- The ternary operator is a conditional operator.
- It is shorthand for `if...else`.
- It takes three operands.
- It returns one value if the condition is true.
- It returns another value if the condition is false.

---

## Key Points

| Part | Simple Meaning |
| :--- | :--- |
| `condition` | The true or false test. |
| `?` | Separates the condition from the true value. |
| `expression1` | Value returned when the condition is true. |
| `:` | Separates the true and false values. |
| `expression2` | Value returned when the condition is false. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let text = (age < 18) ? "Minor" : "Adult";
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let isMember = true;
let discount = isMember ? 0.2 : 0;
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let isMember = false;
let discount = isMember ? 0.2 : 0;
```
</details>

---

## Remember

- Ternary syntax is `(condition) ? expression1 : expression2`.
- It is useful for short `if...else` choices.
- The condition must evaluate to `true` or `false`.
- The first expression is used when true.
- The second expression is used when false.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
