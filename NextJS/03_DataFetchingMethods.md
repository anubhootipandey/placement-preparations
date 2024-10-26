<!-- Data Fetching Methods -->

1. Describe the difference between getStaticProps, getServerSideProps, and getInitialProps.

--> getStaticProps: Fetches data at build time (before deployment) for static pages. It’s fast and great for content that doesn’t change frequently.
getServerSideProps: Fetches data at request time on the server, so the data is fresh each time the page is loaded. It’s good for content that needs to be updated often.
getInitialProps: Works in both server and client environments but isn’t recommended as it doesn’t support static generation.


2. When should you use getStaticProps over getServerSideProps?

--> Use getStaticProps for pages with data that doesn’t change often, like blog posts or product pages. This makes the page load faster. Use getServerSideProps if the data changes frequently and needs to be updated each time the page loads.


3. What is ISR (Incremental Static Regeneration) in Next.js, and how does it work?

--> ISR lets you update static pages after they’re deployed. You can set a time interval for Next.js to re-build a page when it’s requested, ensuring content remains up-to-date without needing to rebuild the whole site.


4. Can you fetch data in a Next.js client component? How?

--> Yes, you can fetch data in a client component using standard React methods like useEffect. This approach is useful for data that doesn’t need to be pre-rendered, like user-specific information or data that updates frequently.


5. Explain the difference between pre-rendering and client-side rendering in Next.js.

--> Pre-rendering generates the HTML for a page before it’s sent to the browser, either at build time or on the server. This makes the page load faster initially.
Client-side rendering fetches data after the page has loaded. While the HTML is generated in the browser, it may make the initial load slower, though it’s good for dynamic content that changes after the page loads.

