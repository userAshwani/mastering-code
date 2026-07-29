# JavaScript Error Object

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Topic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The Error object contains details about an error.**

</div>

---

## Quick Summary

- Error objects contain error information.
- `name` gives the error name.
- `message` gives the error message.
- Different error types can occur.

---

## Key Points

| Feature | Meaning |
| :--- | :--- |
| `name` | Error name. |
| `message` | Error message. |
| `RangeError` | Number outside legal range. |
| `ReferenceError` | Invalid reference. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
try {
  adddlert("Welcome");
} catch (err) {
  console.log(err.name);
}
```
</details>

---

## Remember

- Use error properties to inspect errors.
- `message` explains the problem.
- `name` identifies the type.
- Different mistakes create different errors.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
