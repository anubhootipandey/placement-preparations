<!-- Scope & Closures -->

1. Difference between global, function, and block scope:

--> Global scope: Variables accessible from anywhere in the code.
Function scope: Variables defined inside a function are accessible only within that function.
Block scope: Variables defined within { } (like in if statements or loops) are accessible only within those brackets, if declared with let or const.


2. Hoisting:

--> JavaScript moves variable and function declarations to the top of their scope before code execution. This is why you can call a function before declaring it or use var variables before they’re declared (though they’ll be undefined initially).


3. Example of a closure:

--> function outer() {
    let outerVar = "I’m outside!";
    function inner() {
        console.log(outerVar);
    }
    return inner;
}
const innerFunc = outer();
innerFunc(); // logs "I’m outside!"
Explanation: The inner function remembers outerVar even after outer has finished executing. This is called a closure.


4. Usefulness of closures in real-world applications:

--> Closures help in maintaining state in asynchronous operations, creating private variables, and implementing features like data hiding or factory functions.