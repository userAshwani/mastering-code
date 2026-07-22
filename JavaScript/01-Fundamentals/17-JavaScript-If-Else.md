# JavaScript `else`

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-else-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The JavaScript `else` statement runs code when an `if` condition is false.**

</div>

---

## Quick Summary

- `else` runs code when the `if` condition is false.
- `else if` checks a new condition.
- `if...else` gives two possible paths.
- `if...else if...else` gives multiple paths.
- Conditions are written inside parentheses.

---

## Key Points

| Statement | Simple Meaning |
| :--- | :--- |
| `if` | Runs when the condition is true. |
| `else` | Runs when the condition is false. |
| `else if` | Tests another condition. |
| Code block | The code inside `{}`. |
| Condition | A true or false test. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
if (hour < 18) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
if (time < 10) {
  greeting = "Good morning";
} else if (time < 20) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```
</details>

---

## Remember

- Use `else` for the false result.
- Use `else if` for another condition.
- The final `else` runs when earlier conditions are false.
- Curly braces hold each code block.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
