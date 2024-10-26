<!-- Static Site Generation (SSG) and Incremental Static Regeneration (ISR) -->

1. What is Incremental Static Regeneration, and when should you use it?

--> ISR allows updating parts of a statically generated website without rebuilding the entire site. Use ISR when you need content to stay relatively fresh, like blog posts or product pages that update periodically.


2. Explain how to set up ISR for specific pages.

--> To set up ISR, use getStaticProps in the page component with a revalidate property, like revalidate: 60, which tells Next.js to update the page every 60 seconds if requested.


3. How does Next.js handle revalidation in ISR?

--> When a page with ISR is requested and the revalidation period has passed, Next.js will serve the cached page but also regenerate it in the background, keeping the page updated for the next requests.


4. What are the benefits of ISR over pure SSG or SSR?

--> ISR combines the speed of SSG with the freshness of SSR, allowing static pages to be revalidated without slowing down the load time. It’s efficient for content that updates occasionally.


5. How does ISR affect SEO?

--> ISR is beneficial for SEO because pages are pre-rendered and fast, improving user experience and search engine crawlability. Since content updates periodically, search engines see more relevant information, enhancing SEO.

