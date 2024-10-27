<!-- DOM Manipulation -->

1. Selecting elements in the DOM:

--> Use methods like document.getElementById(), document.querySelector(), and document.querySelectorAll() to grab elements for manipulation.


2. Event delegation:

--> Instead of attaching events to multiple child elements, attach an event to a parent element and check which child was clicked. It’s useful when you have many child elements.
Example: An event on a ul can detect clicks on its li items without attaching individual listeners.


3. Adding, removing, or toggling classes:

--> Use element.classList.add("className"), element.classList.remove("className"), and element.classList.toggle("className") to change classes dynamically.


4. Optimizing DOM manipulation performance:

--> Batch DOM changes together, use documentFragment for multiple updates, and avoid forcing the browser to re-render during each small change.
