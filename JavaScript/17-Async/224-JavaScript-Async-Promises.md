# JavaScript Async Promises

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Async_Promises-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Promises represent the eventual completion or failure of an asynchronous operation and its resulting value.**

</div>

---

## Quick Summary

- A Promise is an object representing eventual success or failure of an async operation.
- Promises have three states: pending, fulfilled, and rejected.
- .then() handles the fulfilled state when Promise resolves successfully.
- .catch() handles the rejected state when Promise rejects or errors occur.
- .finally() runs regardless of whether the Promise resolves or rejects.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Pending State** | Initial state; async operation is still in progress. |
| **Fulfilled State** | Promise resolved; .then() callback is called. |
| **Rejected State** | Promise failed; .catch() callback is called. |
| **Promise.all()** | Resolves when all input Promises resolve simultaneously. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
step1(function(result1) {

  step2(result1, function(result2) {

    step3(result2, function(result3) {

      display(result3);

    });

  });

});
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
step1()

  .then(step2)

  .then(step3)

  .then(display);
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
fetch("fetch.txt")

.then(function(response) {

  return response.text();

})

.then(function(text) {

  myDisplayer(text);

})

.catch(function(error) {

  myDisplayer(error);

});
```
</details>

---

## Remember

- new Promise((resolve, reject) => {}) creates a Promise manually.
- resolve() fulfills the Promise; reject() rejects it with a reason or error.
- Promise chaining connects multiple .then() calls sequentially.
- Promise.race() resolves or rejects with the first settled Promise result.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
