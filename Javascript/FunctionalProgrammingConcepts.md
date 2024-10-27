<!-- Functional Programming Concepts -->

1. Benefits of pure functions:

--> Pure functions are predictable, easier to test, and don’t cause side effects (like changing external data). They make code easier to debug and reuse.


2. Immutability:

--> Immutability means data can’t be changed directly. Instead, create copies of data with updates. Achieve it in JavaScript by using methods like Object.assign, spread syntax, and array methods like map and filter.


3. Map, filter, and reduce methods:

--> map: Transforms each item in an array.
[1, 2, 3].map(x => x * 2); // [2, 4, 6]

filter: Selects items that match a condition.
[1, 2, 3, 4].filter(x => x > 2); // [3, 4]

reduce: Accumulates a result based on each item.
[1, 2, 3, 4].reduce((acc, x) => acc + x, 0); // 10


4. Function composition:

--> Combining multiple functions to perform a series of actions. It allows creating complex operations from simpler ones, a core idea in functional programming.

