# JavaScript AbortController

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-AbortController-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**AbortController allows cancelling in-progress fetch() requests and other abortable async operations.**

</div>

---

## Quick Summary

- AbortController provides a signal object that can be passed to fetch() for cancellation.
- controller.abort() cancels all fetch() calls associated with the controller signal.
- Aborted fetch() Promises reject with an AbortError exception.
- A single AbortController can cancel multiple simultaneous fetch() requests.
- Useful for cancelling outdated requests when user navigates away or types fast.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **new AbortController()** | Creates controller with signal property. |
| **controller.signal** | Passed as signal option to fetch() for cancellation. |
| **controller.abort()** | Cancels all associated fetch() requests immediately. |
| **AbortError** | Error thrown when fetch() is cancelled via abort signal. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const controller = new AbortController();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const controller = new AbortController();

const signal = controller.signal;
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const controller = new AbortController();



fetch("largefile.txt", {

  signal: controller.signal

});
```
</details>

---

## Remember

- Pass { signal: controller.signal } as the second argument to fetch().
- Check if the error name is "AbortError" before reporting it as a real error.
- One AbortController instance can be used to cancel multiple fetch calls.
- Useful in search-as-you-type scenarios to cancel outdated network requests.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
