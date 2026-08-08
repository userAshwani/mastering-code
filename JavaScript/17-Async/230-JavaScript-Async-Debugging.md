# JavaScript Async Debugging

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Async_Debugging-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Debugging async JavaScript requires understanding call stacks, breakpoints, and async-aware DevTools.**

</div>

---

## Quick Summary

- Browser DevTools show async call stacks helping trace the origin of async errors.
- console.log() at each async step traces execution flow and variable states.
- Breakpoints inside async functions can be set in DevTools debugger panel.
- Enable "Async call stack" option in DevTools to see full async trace.
- try-catch blocks isolate and identify specific points of async failure.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Async Call Stack** | DevTools async stacks show chain of async operations. |
| **Debugger Statement** | Pauses execution at a specific line for inspection. |
| **console.log()** | Trace async values and sequence of execution steps. |
| **try-catch Debug** | Wrap await in try-catch to identify failure source. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
console.log("Before fetch");



const promise = fetch("fetch.txt");



console.log("After fetch");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
myDisplayer("Before fetch");



const promise = fetch("fetch.txt");



myDisplayer("After fetch");
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// Async function to download a file

async function loadText(file) {

  const response = await fetch(file);

  myDisplayer(response);

}



myDisplayer("Start");



// Try to load a missing file

loadText("missing.txt");



myDisplayer("Done");
```
</details>

---

## Remember

- Enable async stack traces in Chrome DevTools under Settings for better debugging.
- console.log(await promise) pauses and logs the resolved value in async context.
- Unhandled promise rejections appear as errors in the browser console.
- Use breakpoints inside .then() and catch() for Promise chain debugging.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
