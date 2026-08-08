# JavaScript Async Parallel

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Async_Parallel-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Running multiple async operations in parallel with Promise.all() saves time compared to sequential execution.**

</div>

---

## Quick Summary

- Promise.all() runs multiple Promises simultaneously and waits for all to resolve.
- Sequential await calls run one after another increasing total execution time.
- Parallel Promises with Promise.all() significantly reduce total waiting time.
- Promise.allSettled() waits for all Promises to finish regardless of success or failure.
- Promise.race() resolves or rejects as soon as one Promise settles first.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Promise.all([p1,p2])** | Resolves when ALL Promises resolve; fails on any rejection. |
| **Promise.allSettled()** | Resolves when ALL Promises settle (success or failure). |
| **Promise.race()** | Resolves/rejects with the first settled Promise result. |
| **Promise.any()** | Resolves with first fulfilled Promise; ignores rejections. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// async function to load data

async function loadData() {

  let response1 = await fetch("customer.json");

  let customer = await response1.json();



  let response2 = await fetch("products.json");

  let products = await response2.json();



  let text = "";

  text += JSON.stringify(customer);

  text += JSON.stringify(products);

}



// Call the async load function

loadData();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// async function to load data

async function loadData() {

  let customerPromise = fetch("customer.json");

  let productsPromise = fetch("products.json");



  let customer = await customerPromise;

  let products = await productsPromise;



  let text = "";

  text += JSON.stringify(customer);

  text += JSON.stringify(products);

}



// Call the async load function

loadData();
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// async function to load data

async function loadData() {

  let customerPromise = fetch("customer.json");

  let productsPromise = fetch("products.json");



  let customer = await customerPromise;

  let products = await productsPromise;



  let text =

  "<h3>Customer</h3>" +

  customer.name + ", " +

  customer.city +



  "<h3>Products</h3>" +

  products[0].name + ", " +

  products[1].name + ", " +

  products[2].name;

}



// Call the async load function

loadData();
```
</details>

---

## Remember

- Sequential await runs operations one after another — total time adds up.
- Promise.all() fails immediately if any one Promise rejects.
- Promise.allSettled() is safer when you need all results regardless of errors.
- Prefer Promise.all() over sequential await when tasks are independent of each other.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
