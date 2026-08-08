# JavaScript Promise Reference

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Promise_Reference-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Promise reference lists all static and instance methods available on the JavaScript Promise object.**

</div>

---

## Quick Summary

- Promise.resolve(value) creates an already-resolved Promise wrapping the given value.
- Promise.reject(reason) creates an already-rejected Promise with the given reason.
- Promise.all() resolves when all Promises in the array resolve simultaneously.
- Promise.race() resolves or rejects with the first settled Promise in the array.
- Promise.allSettled() waits for all Promises to finish regardless of outcome.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Promise.resolve(val)** | Returns immediately resolved Promise with value. |
| **Promise.reject(err)** | Returns immediately rejected Promise with reason. |
| **Promise.all([...])** | All must resolve; rejects on first rejection. |
| **Promise.any([...])** | Resolves with first fulfilled; rejects if all fail. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
new Promise(executor)
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const promise = new Promise(function(resolve, reject) {

  const success = true;


  if (success) {

    resolve("Done");

  } else {

    reject("Failed");

  }

});


promise

.then(function(value) {

  myDisplayer(value);

})

.catch(function(error) {

  myDisplayer(error);

});
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
promise.then(onFulfilled)

promise.then(onFulfilled, onRejected)
```
</details>

---

## Remember

- Promise.all() short-circuits and rejects immediately if any single Promise rejects.
- Promise.allSettled() always resolves and returns results for all Promises.
- Instance method .then(fn) returns a new Promise enabling chaining.
- Promise.any() was added in ES2021 and ignores individual rejections.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
