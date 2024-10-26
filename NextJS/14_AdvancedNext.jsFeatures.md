<!-- Advanced Next.js Features -->

1. What is middleware in Next.js, and how does it work?

--> Middleware is code that runs between requests and responses, allowing you to handle tasks like authentication, logging, or redirects before a request reaches the final route.


2. Explain how you would implement middleware for authentication in Next.js.

--> Create middleware in the middleware.js file that checks if a user is authenticated before accessing specific routes. Redirect unauthenticated users to a login page.


3. How does Next.js handle edge functions?

--> Edge functions run at server edges (closer to the user) and enable fast responses and custom logic. Edge functions are often used for personalization or quick data processing near users.


4. What is getStaticProps revalidation, and when would you use it?

--> Revalidation allows you to update static pages at specific intervals without a full rebuild. Use it when you need to periodically refresh content, like for a blog or product listing.


5. How does Next.js handle custom Webpack configuration?

--> Next.js allows custom Webpack configuration by modifying the webpack property in next.config.js. This can be used to add plugins, loaders, or optimize specific aspects of the build process.

