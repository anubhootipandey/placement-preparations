<!-- Data Structures in JavaScript -->


1. Key differences between an array and an object:

--> Array: Ordered collection of items, ideal for lists. Access items by their index, like arr[0].
Object: Collection of key-value pairs, ideal for storing related data. Access items by their key, like obj["key"].


2. Reduce method:

--> reduce processes an array to produce a single value by applying a function to each element.
Example:
const numbers = [1, 2, 3, 4];
const sum = numbers.reduce((acc, curr) => acc + curr, 0); // Result: 10
Use cases: Calculating totals, merging data, transforming arrays into different structures.


3. Main uses of Set and Map:

--> Set: Holds unique values, great for removing duplicates.
Map: Holds key-value pairs with keys of any type, like an improved object.


4. Checking if an object is empty:

--> Use Object.keys(obj).length === 0. If true, the object is empty.

