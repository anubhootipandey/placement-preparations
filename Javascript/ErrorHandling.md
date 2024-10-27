<!-- Error Handling -->


1. try...catch...finally:

--> try runs code; if it throws an error, catch handles it. finally runs code after try and catch, whether an error occurred or not.
Example:
try {
  let result = riskyFunction();
} catch (error) {
  console.error("An error occurred:", error);
} finally {
  console.log("Execution completed.");
}


2. Throw vs. Syntax error:

--> Throw: You can use throw to create your own error, like throw "Custom error".
Syntax error: Happens if there’s a typo or incorrect syntax that prevents the code from running (e.g., if () { is missing a condition).


3. Custom error messages:

--> Use throw new Error("Your message") to create custom errors to describe what went wrong specifically.


4. Importance in asynchronous JavaScript:

--> Errors in async code (like promises) need special handling with .catch() or try...catch (in async functions) since they might fail at unpredictable times.

