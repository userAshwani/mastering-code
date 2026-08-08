# JavaScript Web API Intro

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Web_API_Intro-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**Web APIs extend browser functionality by providing application programming interfaces for complex tasks.**

</div>

---

## Quick Summary

- A Web API is an Application Programming Interface built into the browser or third-party server.
- Browser APIs extend JavaScript capability with features like DOM, Storage, Geolocation, and Fetch.
- Third-party APIs allow integrating external server services like Weather or Maps APIs.
- API methods allow developers to interact with browser hardware and data securely.
- Web APIs typically use JSON format to transmit data back and forth.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **Browser APIs** | Built-in browser interfaces (DOM, Geolocation, Canvas, Storage). |
| **Third-Party APIs** | External web services accessed via URLs (Twitter, Google Maps). |
| **JSON Format** | Standard lightweight data format used across APIs. |
| **HTTP Requests** | Communication channel used to exchange data with web APIs. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
const myElement = document.getElementById("demo");


function getLocation() {

  if (navigator.geolocation) {

    navigator.geolocation.getCurrentPosition(showPosition);

  } else { 
    myElement.innerHTML = "Geolocation is not supported by this browser.";

  }

}


function showPosition(position) {

  myElement.innerHTML = "Latitude: " + position.coords.latitude + 

  "<br>Longitude: " + position.coords.longitude; 
}
```
</details>

---

## Remember

- Web APIs require no installation — browser APIs are built-in automatically.
- Third-party APIs often require API keys for authentication.
- Asynchronous APIs prevent blocking UI rendering during data fetching.
- Browser security policies require HTTPS for sensitive web APIs.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
