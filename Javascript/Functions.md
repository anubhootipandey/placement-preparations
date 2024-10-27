<!-- Functions -->

1. Higher-order function:

--> A function that takes another function as an argument or returns a function. Example: Array.map() is a higher-order function because it takes a function as an argument to apply on each array element.


2. Arrow functions and the this context:

--> Arrow functions (() => {}) don’t have their own this context. They inherit this from the surrounding function or object where they are defined. This is helpful in scenarios where we want this to refer to the current object or scope.


3. Function with arbitrary number of arguments:

--> Use the rest parameter syntax, like function myFunc(...args), to allow a function to accept any number of arguments. args will be an array of all arguments passed.


4. Pure function:

--> A function that, given the same inputs, always returns the same output without any side effects (like modifying external variables). Pure functions are predictable and easy to test, which makes code more reliable.
