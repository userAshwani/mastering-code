# JavaScript HTML DOM Animation

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-DOM_Animation-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**JavaScript creates web animations by changing element styles step by step inside timer functions.**

</div>

---

## Quick Summary

- DOM animations are created by changing inline CSS properties over small time intervals.
- setInterval() repeatedly executes an animation step at set time periods.
- clearInterval() stops the timer when an animation reaches its target position.
- Container elements require CSS position: relative, and animated elements need position: absolute.
- requestAnimationFrame() is an optimized browser method for smoother animations.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **setInterval()** | Runs a function repeatedly at specified millisecond intervals. |
| **clearInterval()** | Stops a timer created by setInterval(). |
| **position: relative** | Required on parent container to bound child positioning. |
| **position: absolute** | Required on target element to allow top/left numeric movement. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<!DOCTYPE html>
<html>
<body>

<h1>My First 
 JavaScript Animation</h1>


<div id="animation">My animation will go here</div>


</body>
</html>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<div id ="container">
&nbsp;&nbsp;<div id ="animate">My 
 animation will go here</div>
</div>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
#container {
&nbsp;&nbsp;width: 400px;
&nbsp;&nbsp;height: 
 400px;
&nbsp; position: relative;
&nbsp; 
 background: yellow;

 }
#animate {
&nbsp; width: 50px;
&nbsp; height: 
 50px;
&nbsp; position: absolute;
&nbsp; 
 background: red;
}
```
</details>

---

## Remember

- Animated child elements must have absolute positioning relative to their container.
- Use top, left, right, or bottom style properties to move elements.
- Always clear the interval timer when the animation endpoint is reached.
- Smaller interval delays produce smoother visual animation movement.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
