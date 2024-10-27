<!-- Asynchronous JavaScript -->

1. Callback function:

--> A callback is a function passed into another function to run later, usually after something has happened. For example, a callback can be used in a setTimeout to run a function after a delay.
Example Use: Fetching data from a server—once the data is ready, the callback handles what to do next.


2. Promises:

--> A promise is an object that represents a task that’s still in progress or completed. It can either resolve (successful) or reject (failed).
Example:
let fetchData = new Promise((resolve, reject) => {
  let data = true;
  if (data) resolve("Data received!");
  else reject("Failed to get data.");
});
fetchData.then(response => console.log(response))
         .catch(error => console.error(error));
Explanation: fetchData will either log "Data received!" if successful or "Failed to get data" if it fails.


3. Async/await:

--> async and await make working with promises easier, so code looks cleaner. await pauses the function until the promise is resolved.
Example:
async function getData() {
  try {
    let response = await fetch("url");
    console.log(response);
  } catch (error) {
    console.error(error);
  }
}
getData();
This reads like synchronous code, which is easier to understand than chaining then and catch.


4. JavaScript Event Loop:

--> The event loop allows JavaScript to handle multiple tasks by using a queue. It quickly processes synchronous tasks first, then checks the queue to process asynchronous tasks, like callbacks and promises, when the main code is idle.

