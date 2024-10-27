<!-- Event Handling -->


1. Common types of events in JavaScript:

--> Click: Triggered when an element is clicked.
Mouseover: Triggered when the mouse hovers over an element.
Keydown: Triggered when a key is pressed on the keyboard.
Submit: Triggered when a form is submitted.


2. Preventing the default action of an event:

--> Use event.preventDefault() to stop the browser’s default behavior for an event, like stopping a form from submitting or a link from navigating.


3. Event bubbling vs. capturing:

--> Bubbling: The event starts at the target element and bubbles up to the ancestors (parents).
Capturing: The event is captured from the root element and goes down to the target element.


4. Handling multiple events on the same element:

--> You can add multiple event listeners to the same element for different event types, or you can use conditional logic to handle multiple events in a single listener.
