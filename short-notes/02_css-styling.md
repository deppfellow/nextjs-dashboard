## This Chapter cover:

- Adding global CSS to application
- Two ways of styling: Tailwind and CSS Modules
- Conditionally add class names with `clsx` packages

## What you've learn in this chapter

- Using `global.css` to add a style css that applied to all routes. Usually its placed in root `layout.tsx`
- Using tailwindcss to styling, by `classname` in each elements
- Using CSS Modules, by creating a `*.modules.css` file and then import in a files. Then `importedName.className` in an element to apply the styling.
- Using `clsx` library to apply conditional styling, using `clsx('default-styles', {conditional-styles})`
