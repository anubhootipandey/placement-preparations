<!-- Server-Side Rendering (SSR) and Static Generation (SSG) -->

1. Describe the difference between SSR and SSG in Next.js.

--> SSR (Server-Side Rendering): The page’s HTML is generated on the server when a user requests it, so the data is always fresh but may load a bit slower.
SSG (Static Site Generation): The HTML is pre-built at build time, which makes it faster since the page is ready ahead of time. However, it’s best for content that doesn’t change often.


2. How does getServerSideProps differ from getStaticProps in terms of execution?

--> getServerSideProps runs on every page request, providing fresh data each time. getStaticProps runs at build time, generating static pages, so the data doesn’t update unless you rebuild or use ISR.


3. What are the pros and cons of SSR vs. SSG?

--> SSR Pros: Data is always fresh, making it good for dynamic pages that need to update frequently (e.g., dashboards).
SSR Cons: Slower initial load time since each page is generated on request.
SSG Pros: Very fast loading since the page is pre-built; good for SEO.
SSG Cons: Content might not be as fresh, so it’s not ideal for frequently changing data.


4. How does ISR (Incremental Static Regeneration) fit into the SSG model?

--> ISR allows Next.js to update static pages after deployment, keeping content up-to-date without rebuilding the whole site. It uses a time interval (revalidate setting) to check if pages need regeneration when visited.


5. Explain the usage of fallback in getStaticPaths for SSG.

--> fallback in getStaticPaths lets Next.js handle pages that aren’t pre-built at build time. If fallback is true, Next.js will generate the page the first time it’s requested. Options include:
true: Builds the page when requested and caches it.
false: Returns a 404 if the page isn’t pre-built.
'blocking': Waits for the page to generate on the server, then serves it to the user.

