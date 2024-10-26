<!-- Image Optimization -->

1. How does Next.js optimize images?

--> Next.js automatically optimizes images by resizing, compressing, and serving them in the best format (like WebP) based on the user’s device. This reduces load time and improves performance.


2. What is the purpose of the next/image component?

--> The next/image component helps with automatic image optimization, including resizing, lazy loading, and responsive support. It’s an easy way to handle optimized images without manual setup.


3. Explain how the blurDataURL property works in next/image.

--> The blurDataURL property provides a low-resolution, blurred placeholder while the main image is loading. It creates a smooth transition effect, making the page look better during image load.


4. How does Next.js handle image resizing and serving optimized images?

--> Next.js dynamically resizes images based on the size specified in next/image and serves them in the best quality and format for the device, reducing load times and saving bandwidth.


5. Can you use external image sources with next/image? If so, how?

--> Yes, Next.js supports external images. You just need to add the domain in next.config.js under images.domains, allowing next/image to optimize and display images from that source.

