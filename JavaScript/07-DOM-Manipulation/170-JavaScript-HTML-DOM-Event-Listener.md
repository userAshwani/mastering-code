# JavaScript HTML DOM Event Listener

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Event_Listener-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**addEventListener() attaches event handlers to elements without overwriting existing event handlers.**

</div>

---

## Quick Summary

- addEventListener() attaches an event handler method to an element node.
- You can add multiple event handlers to the same element without overwriting existing ones.
- The event type is specified without the "on" prefix (e.g. "click" instead of "onclick").
- removeEventListener() detaches an existing event handler method from an element.
- A third boolean parameter controls whether the handler uses capturing (true) or bubbling (false).

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **addEventListener()** | Attaches event handler to element node. |
| **removeEventListener()** | Removes event handler attached by addEventListener(). |
| **Event Type** | Name of event without "on" (e.g., "click", "mouseover"). |
| **Use Capture** | Optional boolean (default false for bubbling, true for capturing). |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
document.getElementById("myBtn").addEventListener("click", displayDate);
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
element.addEventListener(event, function, useCapture);
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
element.addEventListener("click", function(){ alert("Hello World!"); });
```
</details>

---

## Remember

- addEventListener() allows attaching multiple handlers to the exact same event.
- Do not use the "on" prefix for event names in addEventListener().
- removeEventListener() requires passing the exact same function reference.
- Passing anonymous functions to addEventListener prevents removing them later.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
