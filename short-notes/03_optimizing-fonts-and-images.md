## What you'll learn in this chapter

---

[Link to tutorial's chapter](https://nextjs.org/learn/dashboard-app/optimizing-fonts-images)

- Add custom fonts with `next/fonts`
- Add images with `next/images`
- Optimize fonts and images in Next.js

## Notes - Why optimizng fonts

In section `Why optimizing fonts?`, they explain that webs load the fonts in fallback/system fonts first, then replace it with custom fonts after its loaded.

However, Next.js optimize fonts by downloading it ad build time, and then hosts it with other static assets. Its means that there is not additional network requests for fonts that impact performance.

## Notes - Why Optimizing Images

In section `Why optimizing images?`, they explained that using HTML's `<img>` element consequences on us having to:

- Ensure image responsiveness
- Specifying images sizes for different devices
- Prevent layout shift as images load
- Lazy laod images outside user's viewport.

With Next.js' `<Image>`, ts handle all those problems. They also said that its a good practice to set `width` and `height` to avoid layout shift.

## What You've Learn in This Chapter

- Using `next/fonts` to add fonts and optimize them, by downloading it at build time and serve it with other static assets.
- using `next/image` to handle and optimize images.
