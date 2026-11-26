# Part B: Browser DevTools

## B1 - Elements Panel

* **Tag name:** img
* **Attribute:** src="https://dorsu.edu.ph/wp-content/uploads/2023/12/LOGO-1.png"
* **Parent element:** a

**Why did the change disappear after reloading?**

The change disappeared because I only edited the website temporarily using Chrome DevTools. I did not change the original website's source code, so reloading restored the original content.

## B2 - Style Panel

Computed CSS values:

Color:rgb(255, 255, 255) (white)

Font family: Poppins, sans-serif

Font size: 32px

Crossed-out CSS property:

The browser ignored max-height: 60px because another CSS rule sets the maximum height to 180px, and that rule takes priority.

Live CSS change:

I changed the heading's background color to yellow using Chrome DevTools. The change was temporary and only affected the browser display.

## B3 - Network Panel

Website inspected: https://dorsu.edu.ph/

Network Information

Request URL: https://dorsu.edu.ph/
Request Method: GET
Status Code: 200 OK
Content Type: text/html; charset=UTF-8
Server: cloudflare
Main document size: 38.1 kB
Total requests: 82
Total transferred: 2.4 MB
Finish time: 5.3 min

Observation:

The DOrSU website successfully responded with a 200 OK status. The browser loaded 82 requests with a total of 2.4 MB transferred. The Network panel showed a finish time of 5.3 minutes.

## B4 - Console Panel

Website inspected: https://dorsu.edu.ph/

Console observations:

No visible red error messages were found.

JavaScript command console.log("Hello DOrSU!") successfully displayed Hello DOrSU!.

document.title returned D'OrSU - Davao Oriental State University.

window.location.href returned https://dorsu.edu.ph/.

window.location.hostname returned dorsu.edu.ph.

Observation:

The Console panel allows developers to execute JavaScript commands and inspect website information. The commands executed successfully, and no visible red errors were found during inspection.

## B5 - Source Panel

Website inspected: https://dorsu.edu.ph/

JavaScript file inspected: wp-emoji-loader.min.js

Purpose:

This WordPress-generated JavaScript file checks whether the browser supports emojis. It also uses session storage to temporarily save the results of its support tests.

Code observations:

document.querySelector() searches for an HTML element.

JSON.parse() converts JSON text into a JavaScript object.

sessionStorage.setItem() stores information temporarily in the browser session.

Observation:

The Sources panel allows developers to view and inspect the HTML, CSS, and JavaScript files used by a website.



\## DevTools Summary Table



| Panel | What I inspected | Result |

|---|---|---|

| Elements | Website logo | img element with a link parent |

| Styles | Heading CSS | White text, Poppins font, 32px |

| Network | Main website request | GET, 200 OK, 38.1 kB |

| Console | JavaScript commands | Commands executed successfully |

