---
title: HTML5 Web Storage
---
## What is exactly HTML Web Storage?

HTML5 introduces a mechanism to store structured data locally on within user's browser similar to HTTP session cookies.

### Why Web Storage over traditional Cookies?
* Cookies are included with every HTTP request, thereby slowing down our web app by transmitting same data repeatedly.
* Cookies are sent uncrypted over the internet.
* Cookies are limited to about 4KB of data, where as Web Storage ranges from 2MB to 10MB depending upon browser and device(mobile or desktop). More <a href='https://www.html5rocks.com/en/tutorials/offline/quota-research/' target='_blank' rel='nofollow'>here.</a>
* Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

#### HTML Web Storage Objects

HTML web storage provides two objects for storing data on the client:

* window.localStorage - stores data with no expiration date
* window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)

