<!-- Basics of JavaScript -->

1. Differences between var, let, and const.

--> var: Used to declare variables globally or within functions. Variables declared with var are function-scoped and can be updated or redeclared.
let: Block-scoped, meaning it's limited to the block { } in which it’s defined. It can be updated but not redeclared within the same scope.
const: Also block-scoped, but unlike let, it cannot be updated or redeclared. It’s used for values that shouldn’t change (constant values).


2. Difference between == and ===.

--> ==: Loose equality. It compares values after converting them to the same type if they’re different. For example, 5 == "5" is true.
===: Strict equality. It compares both value and type. For example, 5 === "5" is false because one is a number and the other is a string.


3. Checking if a variable is an array.

--> Use Array.isArray(variable). This method returns true if variable is an array, and false otherwise.


4. Concept of coercion in JavaScript.

--> Coercion is when JavaScript converts a value from one type to another automatically. For instance, in 5 + "5", the number 5 is coerced into a string, so the result is "55".

