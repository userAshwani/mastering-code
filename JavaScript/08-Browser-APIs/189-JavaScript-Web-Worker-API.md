# JavaScript Web Worker API

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Web_Workers-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Web Workers run scripts in background threads without blocking the main user interface execution.**

</div>

---

## Quick Summary

- A Web Worker is a JavaScript running in a background thread separate from the main page thread.
- Prevents heavy computation tasks from freezing or slowing down UI rendering.
- new Worker("worker.js") instantiates a new background worker thread.
- postMessage() passes messages and data between main page and worker thread.
- terminate() stops a running web worker immediately from the main thread.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **new Worker(file)** | Creates a background worker thread executing file. |
| **postMessage()** | Sends data to or from a worker thread. |
| **onmessage Event** | Fires when a message is received from worker. |
| **terminate()** | Stops a background worker immediately. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
if (typeof(Worker) !== "undefined") {

  // Yes! Web worker support!

    // Some code.....

 }
 else {

    // Sorry! No Web Worker support..

 }
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
let i = 0;



function timedCount()
{

    
i ++;

    
postMessage(i);

  setTimeout("timedCount()",500);

}



timedCount();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
if (typeof(w) == "undefined") {

    w = new Worker("demo_workers.js");

 }
```
</details>

---

## Remember

- Web Workers cannot access the DOM object, window, or document directly.
- Communication occurs exclusively via postMessage() and onmessage events.
- Ideal for heavy math calculations, data processing, or background tasks.
- Must be loaded from a web server environment due to security restrictions.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
