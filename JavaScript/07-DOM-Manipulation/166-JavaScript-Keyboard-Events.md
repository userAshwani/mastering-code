# JavaScript Keyboard Events

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Keyboard_Events-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Keyboard events respond to user key actions when typing or interacting with focusable elements.**

</div>

---

## Quick Summary

- keydown fires when a keyboard key is initially pressed down.
- keyup fires when a pressed key is released by the user.
- The event.key property contains the string value of the pressed key (e.g., "Enter").
- The event.code property represents the physical physical key code (e.g., "KeyA").
- Keyboard events allow creating custom keyboard shortcuts and accessibility features.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **keydown** | Fires when a key is pressed down. |
| **keyup** | Fires when a key is released. |
| **event.key** | String representing the printed value of the key. |
| **event.code** | String representing the physical key on the keyboard. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<input id="k" type="text" placeholder="Press a key">



<p id="demo"></p>



<script>

const k = document.getElementById("k");



// Let k listen for keydown

k.addEventListener("keydown", function (event) {

// Then display the event.key

&nbsp;&nbsp;document.getElementById("demo").innerHTML = "You pressed: " + event.key;

});

</script>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<input id="in01" type="text" placeholder="Press Enter">



<p id="demo"></p>



<script>

const in01 = document.getElementById("in01");



// Let in01 listen for keydown

in01.addEventListener("keydown", function (event) {

// If event.code was "enter", then display text

&nbsp;&nbsp;if (event.code === "Enter") {

&nbsp;&nbsp;&nbsp;&nbsp;document.getElementById("demo").innerHTML = "Enter was pressed!";

&nbsp;&nbsp;}

});

</script>
```
</details>

---

## Remember

- keydown repeats continuously if a user holds a key down.
- event.key accounts for keyboard layouts and modifier state (Shift/Alt).
- event.code remains identical regardless of keyboard language settings.
- Use preventDefault() on keydown to suppress browser default actions.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
