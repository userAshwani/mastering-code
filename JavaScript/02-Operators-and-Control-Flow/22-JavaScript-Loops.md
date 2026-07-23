# JavaScript Loops

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Loops-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Loops repeat a block of code multiple times, each type suited for a different use case.**

</div>

---

## Quick Summary

- Loops execute a block of code as long as a condition is true.
- JavaScript has five loop types: `for`, `for/in`, `for/of`, `while`, and `do/while`.
- Use `for` when you know how many times to loop.
- Use `while` when the number of iterations is unknown.
- Use `for/in` for object properties and `for/of` for iterable values.

---

## Key Points

| Loop | Best Used For | Key Trait |
| :--- | :--- | :--- |
| `for` | Known number of iterations | Has init, condition, increment |
| `for/in` | Object properties | Iterates over keys |
| `for/of` | Arrays, strings, iterables | Iterates over values |
| `while` | Unknown number of iterations | Checks condition before each run |
| `do/while` | Must run at least once | Checks condition after each run |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
// for loop — runs 5 times
for (let i = 0; i < 5; i++) {
  console.log(i);
}

// for/in — loops over object keys
const person = { name: "John", age: 30 };
for (let key in person) {
  console.log(key + ": " + person[key]);
}

// for/of — loops over array values
const colors = ["red", "green", "blue"];
for (let color of colors) {
  console.log(color);
}

// while — runs while condition is true
let i = 0;
while (i < 3) {
  console.log(i);
  i++;
}

// do/while — always runs at least once
let j = 0;
do {
  console.log(j);
  j++;
} while (j < 3);
```
</details>

---

## Remember

- `for/in` gives you the **key** (property name), not the value directly.
- `for/of` gives you the **value** directly from an iterable.
- `do/while` always executes its body **at least once**, even if the condition is false.
- A missing or wrong condition in `while` can cause an **infinite loop**.
- All loop types support `break` to exit early and `continue` to skip an iteration.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
