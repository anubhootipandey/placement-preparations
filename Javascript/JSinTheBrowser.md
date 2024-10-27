<!-- JavaScript in the Browser -->

1. localStorage vs. sessionStorage:

--> localStorage: Stores data with no expiration date. Data remains even after closing the browser.
sessionStorage: Stores data for the session only. Data is cleared when the browser or tab is closed.


2. Setting, reading, and deleting cookies:

--> Set:
document.cookie = "username=John; expires=Fri, 31 Dec 2024 23:59:59 GMT";
Read:
console.log(document.cookie);
Delete:
document.cookie = "username=John; expires=Thu, 01 Jan 1970 00:00:00 UTC";


3. Fetch API:

--> fetch makes HTTP requests to a server, returning a promise.
Example:
fetch("https://api.example.com/data")
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error(error));


4. Cross-origin requests:

--> JavaScript restricts certain requests to avoid security risks. CORS (Cross-Origin Resource Sharing) is a security feature that controls which external websites can access resources.

