# JavaScript Geolocation API

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-Geolocation_API-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827&labelColor=111827)
![Beginner Friendly](https://img.shields.io/badge/Style-Short_Notes-0EA5E9?style=for-the-badge&logo=readme&logoColor=white&labelColor=111827)
![GitHub Ready](https://img.shields.io/badge/Format-GitHub_Ready-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=111827)

**The Geolocation API allows users to share their geographic position with web applications securely.**

</div>

---

## Quick Summary

- navigator.geolocation checks if the browser supports geographic positioning.
- getCurrentPosition() retrieves the user current latitude and longitude coordinates.
- User permission is strictly required before location data is accessed.
- watchPosition() returns updated position coordinates as the user moves.
- clearWatch() stops an active watchPosition() tracking timer.

---

## Key Points

| Feature / Method | Description |
| :--- | :--- |
| **getCurrentPosition()** | Returns current device latitude and longitude. |
| **watchPosition()** | Continuously monitors and returns updated positions. |
| **clearWatch()** | Stops an ongoing watchPosition() location monitor. |
| **coords.latitude** | Property containing numeric latitude coordinate. |

---

## Simple Example

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
<script>
const x = document.getElementById("demo");
function getLocation() {
  if (navigator.geolocation) {

      navigator.geolocation.getCurrentPosition(showPosition);
  } else {

      x.innerHTML = "Geolocation is not supported by this browser.";

    }
}


 function showPosition(position) {
  x.innerHTML = "Latitude: " + position.coords.latitude + 
  "<br>Longitude: " + position.coords.longitude; 

 }
</script>
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function showError(error) {
  switch(error.code) {
    case error.PERMISSION_DENIED:

        x.innerHTML = "User denied the request for Geolocation."

        break;
    case error.POSITION_UNAVAILABLE:

        x.innerHTML = "Location information is unavailable."
      break;
    case error.TIMEOUT:

        x.innerHTML = "The request to get user location timed out."

        break;
    case error.UNKNOWN_ERROR:
      x.innerHTML = "An unknown error occurred."
      break;

    }

 }
```
</details>

---

<details open>
<summary><strong>💻 Click to Hide/Show Code Example</strong></summary>
<br>

```javascript
function showPosition(position) {
  let latlon = position.coords.latitude + "," + position.coords.longitude;


   let img_url = "https://maps.googleapis.com/maps/api/staticmap?center=

   "+latlon+"&zoom=14&size=400x300&sensor=false&key=YOUR_KEY";


   document.getElementById("mapholder").innerHTML = "<img src='"+img_url+"'>";

 }
```
</details>

---

## Remember

- Geolocation requires explicit user permission before location is revealed.
- HTTPS security is mandatory for Geolocation API access in modern browsers.
- getCurrentPosition() accepts success and error callback functions.
- coords.accuracy indicates coordinate precision in meters.

---

<div align="center">

<a href="https://ashwanitiwari.com/portfolio">
  <img src="https://ashwanitiwari.com/logo.png" alt="Ashwani Tiwari Portfolio" width="120" />
</a>

<br />

**Documented & Maintained by [Ashwani Tiwari](https://ashwanitiwari.com)**  
*Explore full-stack architecture, projects, and client work at [ashwanitiwari.com/portfolio](https://ashwanitiwari.com/portfolio)*

</div>
