<!-- Error Handling and Debugging -->

1. How does Next.js handle 404 errors?

--> Next.js automatically shows a default 404 error page when users try to access a non-existent route.


2. How would you create a custom 404 page in Next.js?

--> Create a custom 404.js file inside the pages directory. This file will be displayed for all 404 errors, allowing you to design a unique error page.


3. How can you manage global error handling in a Next.js application?

--> You can manage global errors by wrapping components with error boundaries or handling errors in API routes. Next.js also supports custom error pages for global errors like 500 (server errors).


4. Explain how to debug API routes in Next.js.

--> To debug API routes, you can use console.log statements, enable debugging tools in your editor, or run the server in development mode for better error visibility.


5. What strategies do you use to handle API errors in Next.js applications?

--> Common strategies include using try-catch blocks to handle errors in API routes, returning informative error messages, and setting up error boundaries to prevent the app from crashing on errors.

