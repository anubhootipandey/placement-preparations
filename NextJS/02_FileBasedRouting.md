<!-- File-Based Routing -->

1. How does routing work in Next.js?

--> In Next.js, routing is based on files and folders inside a special pages folder. Each file inside pages becomes a page in the app. For example, pages/about.js would be accessible at /about in the browser.


2. How would you create dynamic routes in Next.js?

--> Dynamic routes let you create pages based on variable content. To do this, you make a folder with brackets, like [id], in the pages directory. If you have a file pages/posts/[id].js, you could visit posts/1 or posts/2 for different posts, with id representing each unique post.


3. What is the getStaticPaths function used for in Next.js?

--> getStaticPaths is used with dynamic routes to tell Next.js which pages to build ahead of time. For example, if you have multiple posts, getStaticPaths will provide all the IDs for those posts so that Next.js can pre-render them.


4. Explain the purpose of the useRouter hook in Next.js.

--> The useRouter hook is a tool in Next.js to access information about the current route. You can use it to get the current path or the dynamic parameters (like id in [id].js). This helps with things like loading data based on the current route.


5. How can you create nested routes in Next.js?

--> To create nested routes, you organize folders within the pages directory. For example, if you want /blog/posts, you could create a blog folder with a posts.js file inside it (pages/blog/posts.js).

