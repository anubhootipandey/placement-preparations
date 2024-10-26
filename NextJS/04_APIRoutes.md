<!-- API Routes -->

1. What are API routes in Next.js, and how do you create them?

--> API routes in Next.js let you create backend functions inside your app to handle things like data processing or connecting with databases. To make one, create a file in the pages/api folder, like pages/api/hello.js. This file will be treated as an API endpoint at /api/hello.


2. How do you handle middleware in Next.js API routes?

--> Middleware in API routes is a function that runs before your main API function. It can check data, authenticate users, or log information. Middleware functions can be written in the API file itself or imported to be used across multiple routes.


3. How does Next.js manage error handling in API routes?

--> In API routes, you can handle errors by using try-catch blocks and sending back error messages in the response. For example, res.status(500).json({ message: 'Error' }) will send a 500 error and message if something goes wrong.


4. What are some use cases for Next.js API routes?

--> Common uses include handling form submissions, authenticating users, retrieving or updating data from a database, and connecting to third-party APIs.


5. Explain the concept of Middlewares in Next.js API routes.

--> Middleware functions act as “filters” that process requests before they reach the main API function. They are useful for things like authentication, checking permissions, or validating data before it’s used in the main function.

