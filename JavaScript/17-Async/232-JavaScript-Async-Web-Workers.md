# JavaScript Async Web Workers

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Async_Web_Workers-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Web Workers run JavaScript in a separate background thread keeping the main UI thread responsive.**

</div>

---

## Quick Summary

- Web Workers execute code in a background thread independently from the main thread.
- Prevents CPU-intensive tasks from blocking the main UI and event handling.
- new Worker("file.js") instantiates a background worker thread from a script file.
- Main thread and worker communicate via postMessage() and onmessage event handler.
- Workers do not have access to the DOM, window, or document objects.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **new Worker(file)** | Starts a background worker thread executing file. |
| **postMessage(data)** | Sends data message between main thread and worker. |
| **onmessage** | Event handler that fires when message is received. |
| **terminate()** | Stops the worker thread from the main thread side. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function calculate() {

  let total = 0;

  for (let i = 0; i < 5e9; i++) {

    total += i;

  }

  return total;

}



myDisplayer("Calculating...");



let result = calculate();



myDisplayer(result);
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
myDisplayer("Start");



setTimeout(function () {

  myDisplayer("Timer")}, 1000);



let i = 5e9;

while (--i > 0);



myDisplayer("Finished");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
if (typeof(Worker) !== "undefined") {

  myDisplayer("Web Workers are supported.");

} else {

  myDisplayer("Web Workers are not supported.");

}
```
</details>

---

## Remember

- Workers run in strict isolation — no DOM, no window, no document access.
- Communication is through structured clone algorithm via postMessage().
- Ideal for heavy JSON processing, math computations, or image processing tasks.
- Always terminate workers when done to free up system resources.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
