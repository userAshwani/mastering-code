# JavaScript HTML DOM Events

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-DOM_Events-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**HTML DOM events enable scripts to react dynamically to user actions on HTML elements.**

</div>

---

## Quick Summary

- Events can be assigned to HTML elements using inline event attributes or JavaScript properties.
- element.onclick = functionName assigns a JavaScript function handler directly.
- Form events like onsubmit, onfocus, and onblur trigger on form control interactions.
- Media events like onplay and onpause manage audio and video playback.
- Assigning handlers via JavaScript properties keeps HTML markup clean.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **onsubmit** | Fires when a form submit button is clicked. |
| **onfocus** | Fires when an element gains user focus. |
| **onblur** | Fires when an element loses user focus. |
| **oninput** | Fires immediately when input element value changes. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
onclick=JavaScript
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<!DOCTYPE html>
<html>

<body>


<h1 onclick="this.innerHTML = 'Ooops!'">Click on this text!</h1>


</body>
</html>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<!DOCTYPE html>
<html>
<body>


<h1 onclick="changeText(this)">Click on this text!</h1>

 
<script>

function changeText(id) {


&nbsp;&nbsp;id.innerHTML = "Ooops!";

}

</script>


</body>
</html>
```
</details>

---

## Remember

- JavaScript event properties should be written in lowercase (e.g. onclick).
- oninput triggers on every keystroke, whereas onchange triggers on focus loss.
- Setting an event property to null removes the handler.
- Combining events with DOM manipulation enables rich interactive pages.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
