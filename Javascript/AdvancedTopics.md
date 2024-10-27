<!-- Advanced Topics -->


1. Destructuring:

--> Destructuring allows you to unpack values from arrays or properties from objects directly into variables.
Examples:
const [a, b] = [1, 2]; // Array destructuring
const { name, age } = { name: "Alice", age: 25 }; // Object destructuring


2. Spread and rest operators:

--> Spread (...): Expands elements of an array or object.

const arr1 = [1, 2];
const arr2 = [...arr1, 3, 4]; // [1, 2, 3, 4]

Rest (...): Gathers multiple elements into an array.

function sum(...numbers) {
  return numbers.reduce((acc, num) => acc + num, 0);
}


3. Template literals:

--> Template literals use backticks (`) and allow embedding variables and expressions directly inside strings with ${}.
Example:
const name = "Alice";
console.log(`Hello, ${name}!`); // "Hello, Alice!"


4. Generator function:

--> A generator is a special function that can pause and resume its execution, yielding multiple values over time.
Example:
function* count() {
  yield 1;
  yield 2;
  yield 3;
}
for (let num of count()) {
  console.log(num); // Outputs 1, 2, 3
}
Use case: Useful for handling sequences or streams of data step-by-step.