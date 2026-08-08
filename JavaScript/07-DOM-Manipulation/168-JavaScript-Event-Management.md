# JavaScript Event Management

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Event_Management-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Event management covers event propagation phases, event delegation, and controlling default behaviors.**

</div>

---

## Quick Summary

- Event propagation occurs in two phases: capturing (downwards) and bubbling (upwards).
- Event bubbling means an event triggers on the child element then bubbles up to ancestors.
- stopPropagation() prevents an event from continuing its propagation up or down the DOM tree.
- preventDefault() stops the default browser action associated with an event.
- Event delegation attaches a single handler to a parent to manage events on multiple children.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Event Bubbling** | Events fire on target element first, then propagate upwards. |
| **Event Capturing** | Events propagate downwards from root to target element. |
| **stopPropagation()** | Prevents further propagation of current event. |
| **preventDefault()** | Cancels default browser behavior for the event. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<button id="btn">Click</button>

<p id="demo"></p>

<script>
const btn = document.getElementById("btn");

// Listen for click event
btn.addEventListener("click", myFunction);

function myFunction() {
  document.getElementById("demo").innerHTML = "Clicked!";
}
</script>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<button id="add">Add</button>
<button id="remove">Remove</button>
<button id="test">Test click</button>

<p id="demo"></p>

<script>
const test = document.getElementById("test");
const remove = document.getElementById("remove");
const add = document.getElementById("add");

function myFunction() {
  document.getElementById("demo").innerHTML += "Hello!";
}

add.addEventListener("click", function () {
  test.addEventListener("click", myFunction);
});

remove.addEventListener("click", function () {
  test.removeEventListener("click", myFunction);
});
</script>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<a href="https://example.com" id="link">Go to Link</a>

<p id="demo"></p>

<script>
const link = document.getElementById("link");

link.addEventListener("click", function(event) {
  event.preventDefault();
  document.getElementById("demo").innerHTML = "Default link action prevented!";
});
</script>
```
</details>

---

## Remember

- By default, addEventListener() uses the event bubbling phase.
- Event delegation reduces memory overhead when handling many list or table items.
- target refers to the actual element clicked, while currentTarget is where handler is attached.
- preventDefault() will not stop event bubbling; use stopPropagation() for that.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
