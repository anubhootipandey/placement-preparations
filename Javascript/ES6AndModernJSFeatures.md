 <!-- ES6+ and Modern JavaScript Features -->


1. Optional chaining:

--> Optional chaining (?.) safely accesses nested properties. If any part is undefined or null, it stops and returns undefined instead of an error.
Example:
const user = { profile: { name: "Alice" } };
console.log(user.profile?.name); // "Alice"
console.log(user.address?.city); // undefined, no error


2. Nullish coalescing operator (??):

--> This operator returns the right-hand value if the left-hand is null or undefined, otherwise, it returns the left-hand value.
Example:
let name = null;
console.log(name ?? "Default Name"); // "Default Name"


3. Dynamic imports:

Allows importing modules when needed, not at the beginning of a file. Useful for performance, especially with large files or specific user actions.
Example:
import("./module.js").then(module => {
  module.function();
});


4. JavaScript classes vs. constructor functions:

--> Classes are a modern, cleaner way to create objects and add methods to them.
Constructor functions achieve the same but use a more manual approach.
Example:
class Person {
  constructor(name) {
    this.name = name;
  }
  greet() {
    return `Hello, ${this.name}`;
  }
}
const person = new Person("Alice");

