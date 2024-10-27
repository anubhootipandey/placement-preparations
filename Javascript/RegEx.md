<!-- Regular Expressions (RegEx) -->

1. Regular expression:

--> A pattern used to match text. RegEx is helpful for validating formats, searching, and replacing text.


2. Using the test method:

--> test checks if a pattern exists in a string, returning true or false.
Example:
/hello/.test("hello world"); // true


3. Flags in regular expressions:

--> Flags modify how RegEx behaves:
g (global): Finds all matches, not just the first.
i (ignore case): Case-insensitive match.
m (multi-line): Allows matching across lines.


4. Using RegEx to validate an email address:

--> Example:
const emailPattern = /^[\w-\.]+@([\w-]+\.)+[\w-]{2,4}$/;
emailPattern.test("example@example.com"); // true if valid
This checks for a basic email structure: text, @, domain, and extension.
