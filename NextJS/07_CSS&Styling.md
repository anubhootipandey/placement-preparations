<!-- CSS and Styling -->

1. How do you add global CSS in a Next.js application?

--> Global CSS is added in the _app.js file by importing a CSS file, like import '../styles/globals.css'. This CSS will apply across the whole app.


2. What are the differences between using CSS Modules and styled-jsx in Next.js?

--> CSS Modules provide scoped styles for individual components, meaning styles in a module file only affect that specific component. styled-jsx is built into Next.js and allows writing scoped CSS directly in JavaScript files, making styles specific to the component they’re included in.


3. How can you add third-party CSS libraries to a Next.js project?

--> You can add libraries like Bootstrap or Tailwind by installing them via npm and importing them in _app.js or specific component files.


4. What is styled-jsx, and how does it work in Next.js?

--> styled-jsx is a CSS-in-JS solution that allows writing scoped CSS within components. Styles are added with <style jsx>{...}</style> tags, and they only apply to the component they’re written in.


5. How can you implement custom styling for specific pages in Next.js?

--> You can add CSS Modules to each page component or use styled-jsx within a page component for page-specific styles.


