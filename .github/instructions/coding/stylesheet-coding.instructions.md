---
applyTo: '**/*.css, **/*.scss, **/*.less, **/*.sass'
---

# Stylesheet Coding Standards

## General Guidelines

- Use consistent indentation (2 spaces)
- Follow BEM (Block Element Modifier) naming conventions for class names where applicable
- Use lowercase for class and ID names
- Use hyphens (-) to separate words in class and ID names (e.g., `.my-class-name`)
- Use full class names instead of ampersand(&) nesting for better readability, only use with pseudo-classes(e.g., `&:hover`, `&:focus`) For example:

```css/scss
.my-class-name {
  color: blue;

  .my-class-name--modifier {
    color: red;

    &:hover {
      color: green;
    }
  }
}
```

- Avoid using IDs for styling; prefer classes instead
- Keep selectors as short and specific as possible
- Avoid using `!important` unless absolutely necessary
- Group related styles together for better organization
- Use comments to separate sections and explain complex styles
- Minimize the use of global styles; prefer component-scoped styles
- Use variables for colors, fonts, and other reusable values (e.g., CSS variables, SASS/LESS variables)
- Optimize for performance by minimizing the number of selectors and avoiding deep nesting
- Use shorthand properties where possible (e.g., `margin`, `padding`, `border`)
- Ensure styles are responsive and adapt to different screen sizes using media queries
- Validate CSS using tools like W3C CSS Validator to ensure code quality and standards compliance
- Regularly review and refactor styles to remove unused or redundant code
