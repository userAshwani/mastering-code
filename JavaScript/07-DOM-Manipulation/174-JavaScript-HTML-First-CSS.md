# JavaScript HTML-First CSS

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-HTML_First_CSS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**HTML-First CSS uses modern CSS layout and state pseudo-classes to handle interactive UI changes without JavaScript.**

</div>

---

## Quick Summary

- Modern CSS handles animation, layout, and UI state toggling without JavaScript.
- CSS pseudo-classes like :hover, :focus, and :checked manage element states.
- CSS Grid and Flexbox handle responsive web layouts natively.
- @media (prefers-color-scheme) handles light/dark themes without scripts.
- CSS transitions and animations create smooth visual effects cleanly.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **:checked** | Toggle UI states (like checkboxes or accordions) using pure CSS. |
| **:focus-within** | Styles parent container when any child element receives focus. |
| **prefers-color-scheme** | Detects OS theme preference natively in CSS. |
| **transition** | Animates CSS property changes smoothly without JS loops. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<style>

button:hover {

&nbsp;&nbsp;background-color:#059862;

}

</style>



<button>Hover Over Me</button>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<style>

.box {

&nbsp;&nbsp;width:100px;

&nbsp;&nbsp;height:100px;

&nbsp;&nbsp;background-color:#04AA6D;

&nbsp;&nbsp;transition:width 0.5s;

}



.box:hover {

&nbsp;&nbsp;width:200px;

}

</style>



<div class="box"></div>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<style>

.menu-content {

&nbsp;&nbsp;display:none;

}



.menu:hover .menu-content {

&nbsp;&nbsp;display:block;

}

</style>



<div class="menu">

&nbsp;&nbsp;Menu

&nbsp;&nbsp;<div class="menu-content">

&nbsp;&nbsp;&nbsp;&nbsp;<a href="#">Link 1</a>

&nbsp;&nbsp;&nbsp;&nbsp;<a href="#">Link 2</a>

&nbsp;&nbsp;</div>

</div>
```
</details>

---

## Remember

- Use CSS pseudo-classes to handle UI states before reaching for JavaScript.
- :checked pseudo-class with hidden checkboxes enables CSS-only toggle widgets.
- CSS transitions perform better than JS setInterval animations.
- Delegating visual state to CSS improves web application responsiveness.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
