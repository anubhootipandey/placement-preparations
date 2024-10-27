<!-- Objects and Prototypes -->

1. Creating an object in JavaScript:

--> Object literal: { key: "value" }

Constructor function:

--> function Person(name) {
    this.name = name;
}
const person1 = new Person("Alice");


2. Prototype chain and inheritance:

--> In JavaScript, objects can inherit properties and methods from another object, known as their prototype. When you access a property on an object, JavaScript checks that object’s properties, and if not found, it looks up the prototype chain until it finds it or reaches the top (usually Object.prototype).


3. The this keyword inside an object’s method:

--> this refers to the object that is calling the method. For example, if person.sayHello() is called, this inside sayHello refers to person.


4. How the new keyword works:

--> new creates a new object and sets its prototype to the constructor function’s prototype property. It also assigns this within the constructor function to the new object, allowing properties to be attached to it. Finally, it returns the new object.
