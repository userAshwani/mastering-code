# JavaScript Popup Alerts

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Popup_Alerts-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript provides alert, confirm, and prompt popup boxes to display messages or gather user inputs.**

</div>

---

## Quick Summary

- alert() displays a dialog box with a specified message and an OK button.
- confirm() displays a dialog box with OK and Cancel buttons, returning true or false.
- prompt() displays a dialog box asking the user for text input value.
- Popup boxes block user interface execution until dismissed.
- Line breaks can be added inside popup message text using \n.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **alert("message")** | Displays an alert box with message and OK button. |
| **confirm("question")** | Returns true if OK clicked, false if Cancel clicked. |
| **prompt("msg", "default")** | Returns input string if OK clicked, null if Cancel clicked. |
| **\n Line Break** | Inserts a line break inside popup text. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
window.alert("sometext");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
alert("I am an alert box!");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
window.confirm("sometext");
```
</details>

---

## Remember

- Popup boxes pause script execution until the user responds.
- confirm() is ideal for confirming destructive user actions.
- prompt() returns null if the user clicks Cancel.
- Avoid overusing modal popup boxes as they interrupt user workflow.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
