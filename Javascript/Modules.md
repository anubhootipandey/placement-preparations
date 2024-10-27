<!-- Modules -->

1. export keyword:

--> export allows you to make a function, variable, or class available to other files.
Example:
export const greet = () => "Hello!";


2. Default vs. named exports:

--> Default export: Exports a single item as the main export (useful when there’s only one export).

export default function greet() { return "Hello!"; }
Named export: Allows exporting multiple items by name.
export const greet = () => "Hello!";
export const farewell = () => "Goodbye!";


3. Importing a function from another file:

Example:
import { greet } from './file.js'; // Named export
import greet from './file.js';     // Default export


4. Benefits of modules:

--> Modules organize code, prevent global variable conflicts, and make it easier to maintain, test, and reuse code across files.

