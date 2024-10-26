 <!-- Internationalization (i18n) -->

1. How does Next.js handle internationalization?

--> Next.js has built-in support for internationalization (i18n), making it easy to build sites that support multiple languages. It provides tools for managing translations and switching languages based on user preferences or location.


2. What is next.config.js used for in i18n?

--> The next.config.js file is used to configure i18n settings, like defining which languages (locales) your site supports and setting the default language.


3. How would you set up multiple language support in Next.js?

--> To add multiple languages, configure i18n in next.config.js by specifying supported locales and default locale. Then, use translation libraries like react-intl or next-i18next to manage translations across components.


4. What are the challenges of implementing i18n in a Next.js app?

--> Challenges include managing translations, handling right-to-left text for languages like Arabic, ensuring SEO compatibility across languages, and keeping translations up-to-date.


5. How does Next.js manage routing for different locales?

--> Next.js automatically handles locale-based routing. It appends the language code to URLs (e.g., /en/about for English and /es/about for Spanish) so users can access different language versions of each page.

