# JavaScript Mouse Events

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Mouse_Events-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Mouse events trigger JavaScript functions when users move, click, or drag the mouse over elements.**

</div>

---

## Quick Summary

- click fires when an element is clicked with the primary mouse button.
- dblclick fires when an element is double-clicked in rapid succession.
- mousedown and mouseup trigger when mouse buttons are pressed or released.
- mouseenter and mouseleave fire when moving the pointer into or out of an element.
- mousemove fires continuously whenever the mouse pointer moves inside an element.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **click** | Triggered by pressing and releasing a mouse button on an element. |
| **dblclick** | Triggered by double clicking an element. |
| **mouseenter** | Fires when mouse enters element area (does not bubble). |
| **mouseleave** | Fires when mouse leaves element area (does not bubble). |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<div id="box" style="width:200px;height:100px;padding:16px;border:1px solid #000;">

Move mouse over this box

</div>


<script>

const box = document.getElementById("box");


// Let box listen for mouseover

box.addEventListener("mouseover", function () {

&nbsp;&nbsp;box.innerHTML = "Mouse is over me!";

});


// Let box listen for mouseout

box.addEventListener("mouseout", function () {

&nbsp;&nbsp;box.innerHTML = "Mouse is out!";

});

</script>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<p id="demo">Move the mouse in this window!</p>


<script>

// Let document listen for mousemove

document.addEventListener("mousemove", function (event) {

&nbsp;&nbsp;document.getElementById("demo").innerHTML =

&nbsp;&nbsp;"X: " + event.clientX + " Y: " + event.clientY;

});

</script>
```
</details>

---

## Remember

- mouseenter and mouseleave do not bubble to parent elements.
- mouseover and mouseout bubble up through nested DOM elements.
- Mouse events provide coordinates like clientX, clientY, pageX, and pageY.
- button property identifies which mouse button triggered the event.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
