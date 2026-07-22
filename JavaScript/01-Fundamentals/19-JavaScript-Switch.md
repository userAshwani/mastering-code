# JavaScript Switch

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Switch-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The JavaScript `switch` statement selects code blocks by matching an expression with cases.**

</div>

---

## Quick Summary

- `switch` selects one or more code blocks to run.
- The expression is evaluated once.
- Each `case` is compared with the expression value.
- `break` stops the switch block.
- `default` runs when no case matches.

---

## Key Points

| Keyword | Simple Meaning |
| :--- | :--- |
| `switch` | Starts the switch statement. |
| `case` | Defines a value to match. |
| `break` | Stops execution inside the switch block. |
| `default` | Runs when no case matches. |
| `===` | Switch uses strict comparison. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
switch (new Date().getDay()) {
  case 0:
    day = "Sunday";
    break;
  case 1:
    day = "Monday";
    break;
  case 2:
    day = "Tuesday";
    break;
  case 3:
    day = "Wednesday";
    break;
  case 4:
    day = "Thursday";
    break;
  case 5:
    day = "Friday";
    break;
  case 6:
    day = "Saturday";
}
```
</details>

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
switch (new Date().getDay()) {
  case 6:
    text = "Today is Saturday";
    break;
  case 0:
    text = "Today is Sunday";
    break;
  default:
    text = "Looking forward to the Weekend";
}
```
</details>

---

## Remember

- `switch` is useful for many possible values.
- `break` prevents fall-through.
- `default` is optional.
- Multiple cases can share the same code block.
- Case matching uses strict comparison.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
